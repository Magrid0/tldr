# stratis

> Gestisci pool di archiviazione locali e volumi usando il gestore di archiviazione Stratis.
> I volumi Stratis usano il filesystem XFS e richiedono il servizio `stratisd`.
> Maggiori informazioni: <https://stratis-storage.github.io/howto/>.

- Avvia il servizio Stratis (deve essere attivo prima di gestire pool o volumi):

`sudo systemctl start stratisd`

- Crea un pool di archiviazione da uno o più dispositivi:

`sudo stratis pool create {{nome_pool}} {{/dev/sdX}} {{/dev/sdY}}`

- Crea un filesystem (volume) in un pool:

`sudo stratis filesystem create {{nome_pool}} {{nome_volume}}`

- Elenca tutti i filesystem Stratis:

`sudo stratis filesystem list`

- Formatta e monta un volume Stratis manualmente:

`sudo mkfs.xfs /dev/stratis/{{nome_pool}}/{{nome_volume}} && sudo mount /dev/stratis/{{nome_pool}}/{{nome_volume}} {{/mnt/destinazione}}`

- Aggiunge un volume a `/etc/fstab` per il montaggio all'avvio:

`echo /dev/stratis/{{nome_pool}}/{{nome_volume}} {{/mnt/destinazione}} xfs defaults,x-systemd.requires=stratisd.service 0 0 | sudo tee {{[-a|--append]}} /etc/fstab`

- Estende un pool esistente aggiungendo un nuovo dispositivo:

`sudo stratis pool add-data {{nome_pool}} {{/dev/sdZ}}`

- Elimina un volume:

`sudo stratis filesystem destroy {{nome_pool}} {{nome_volume}}`
