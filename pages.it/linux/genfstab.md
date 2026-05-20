# genfstab

> Genera output adatto per l'aggiunta al file `/etc/fstab`.
> Maggiori informazioni: <https://manned.org/genfstab>.

- Genera il file `/etc/fstab` usando gli UUID dei volumi durante un'installazione di Arch Linux (richiede permessi di root):

`genfstab -U {{/mnt}} >> {{/mnt/etc/fstab}}`

- Mostra output compatibile con fstab basato su etichette dei volumi:

`genfstab -L {{path/to/mount_point}}`

- Mostra output compatibile con fstab basato su UUID dei volumi:

`genfstab -U {{path/to/mount_point}}`

- Mostra output compatibile con fstab basato sull'identificatore specificato:

`genfstab -t {{LABEL|UUID|PARTLABEL|PARTUUID}}`

- Aggiunge un volume nel file `/etc/fstab` per montarlo automaticamente:

`genfstab -U {{path/to/mount_point}} | sudo tee -a /etc/fstab`
