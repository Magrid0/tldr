# lvconvert

> Converte o modifica il tipo, la ridondanza o lo stato dei volumi logici.
> Maggiori informazioni: <https://manned.org/lvconvert>.

- Converte un volume logico lineare in RAID1 (aggiunge un mirror: due copie totali):

`sudo lvconvert --type raid1 {{[-m|--mirrors]}} 1 {{/dev/vg_name/lv_name}}`

- Rimuove il mirroring e converte di nuovo in un volume logico lineare:

`sudo lvconvert {{[-m|--mirrors]}} 0 {{/dev/vg_name/lv_name}}`

- Unisce uno snapshot di nuovo nel suo volume logico di origine (si applica alla prossima attivazione):

`sudo lvconvert --merge {{/dev/vg_name/snapshot_lv}}`

- Ripara un volume logico RAID degradato:

`sudo lvconvert --repair {{/dev/vg_name/lv_name}}`

- Converte un volume logico esistente in un thin pool con un LV di metadati separato:

`sudo lvconvert --type thin-pool --poolmetadata {{/dev/vg_name/pool_metadata_lv}} {{/dev/vg_name/pool_lv}}`
