# parted

> Programma per la manipolazione delle partizioni.
> Vedi anche: `parted`, `partprobe`.
> Maggiori informazioni: <https://www.gnu.org/software/parted/parted.html>.

- Avvia la modalità interattiva con il disco specificato selezionato:

`sudo parted {{/dev/sdX}}`

- [I]nterattivo: mostra informazioni sulla partizione in modalità interattiva:

`print`

- [I]nterattivo: seleziona un disco in modalità interattiva:

`select {{/dev/sdX}}`

- [I]nterattivo: crea una partizione da 16 GB con il filesystem specificato in modalità interattiva (tabella partizioni `GPT`):

`mkpart {{nome_partizione}} {{btrfs|ext2|ext3|ext4|fat16|fat32|hfs|hfs+|linux-swap|ntfs|reiserfs|udf|xfs}} {{0%}} {{16G}}`

- [I]nterattivo: crea una partizione da 16 GB con il filesystem specificato in modalità interattiva (tabella partizioni `MBR`):

`mkpart {{primary|logical|extended}} {{btrfs|ext2|ext3|ext4|fat16|fat32|hfs|hfs+|linux-swap|ntfs|reiserfs|udf|xfs}} {{0%}} {{16G}}`

- [I]nterattivo: ridimensiona una partizione in modalità interattiva:

`resizepart {{/dev/sdXN}} {{posizione_fine_partizione}}`

- [I]nterattivo: rimuovi una partizione in modalità interattiva:

`rm {{/dev/sdXN}}`

- [I]nterattivo: mostra aiuto:

`?`
