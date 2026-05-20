# ceph

> Un sistema di archiviazione unificato.
> Maggiori informazioni: <https://docs.ceph.com/en/latest/man/8/ceph/>.

- Verifica lo stato di salute del cluster:

`ceph status`

- Verifica le statistiche di utilizzo del cluster:

`ceph df`

- Ottiene le statistiche per i placement group in un cluster:

`ceph pg dump --format {{plain}}`

- Crea un pool di archiviazione:

`ceph osd pool create {{pool_name}} {{page_number}}`

- Elimina un pool di archiviazione:

`ceph osd pool delete {{pool_name}}`

- Rinomina un pool di archiviazione:

`ceph osd pool rename {{current_name}} {{new_name}}`

- Ripara automaticamente l'archiviazione del pool:

`ceph pg repair {{pool_name}}`
