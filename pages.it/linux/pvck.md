# pvck

> Controlla e ripara i metadati LVM sui volumi fisici.
> Maggiori informazioni: <https://manned.org/pvck>.

- Stampa le intestazioni e strutture LVM su disco (etichetta, intestazione PV, intestazione MDA, area metadati):

`sudo pvck {{/dev/sdXN}} --dump headers`

- Stampa il testo dei metadati VG correnti:

`sudo pvck {{/dev/sdXN}} --dump metadata`

- Elenca tutte le versioni dei metadati trovate nell'area metadati:

`sudo pvck {{/dev/sdXN}} --dump metadata_all`

- Cerca posizioni comuni per metadati quando le intestazioni potrebbero essere danneggiate e salva in un file:

`sudo pvck {{/dev/sdXN}} --dump metadata_search {{[-f|--file]}} {{percorso/metadata.txt}}`

- Seleziona la seconda area metadati (mda2) durante la stampa dei metadati:

`sudo pvck {{/dev/sdXN}} --dump metadata --settings "mda_num=2"`

- Ripara intestazioni e metadati usando un file di metadati di input (usare con cautela):

`sudo pvck {{/dev/sdXN}} --repair {{[-f|--file]}} {{percorso/file_metadati}}`

- Ripara solo l'intestazione PV e l'intestazione etichetta:

`sudo pvck {{/dev/sdXN}} --repairtype pv_header`
