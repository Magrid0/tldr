# vgcfgbackup

> Esegue il backup dei metadati di configurazione del volume group in file (non dati utente).
> Maggiori informazioni: <https://manned.org/vgcfgbackup>.

- Esegue il backup dei metadati per tutti i volume group (in `/etc/lvm/backup/` per impostazione predefinita):

`sudo vgcfgbackup`

- Esegue il backup dei metadati per un volume group specifico:

`sudo vgcfgbackup {{nome_vg}}`

- Scrive il backup in un file specifico:

`sudo vgcfgbackup {{[-f|--file]}} {{percorso/del/backup}} {{nome_vg}}`

- Esegue il backup di più VG usando un template per il nome del file (`%s` diventa il nome VG):

`sudo vgcfgbackup {{[-f|--file]}} {{/tmp/vg-backup-%s}} {{vg1 vg2 ...}}`

- Aumenta la verbosità (ripeti `-v` per più dettagli):

`sudo vgcfgbackup {{[-v|--verbose]}} {{nome_vg}}`
