# fdisk

> Gestisce le tabelle delle partizioni e le partizioni su un disco di archiviazione.
> Vedi anche: `partprobe`, `parted`, `cfdisk`.
> Maggiori informazioni: <https://manned.org/fdisk>.

- Elenca le partizioni:

`sudo fdisk {{[-l|--list]}}`

- Avvia il manipolatore interattivo di partizioni:

`sudo fdisk {{/dev/sdX}}`

- Apre un [m]enu di aiuto:

`<m>`

- Visualizza la [p]tabella delle partizioni:

`<p>`

- Crea una [n]uova partizione:

`<n>`

- Seleziona una partizione da [e]liminare:

`<d>`

- [s]crive le modifiche effettuate:

`<w>`

- Scarta le modifiche effettuate ed [e]sci:

`<q>`
