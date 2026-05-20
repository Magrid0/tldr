# gdisk

> Strumento di partizionamento dei dischi GPT (GUID Partition Table).
> Vedi anche: `cfdisk`, `fdisk`, `parted`.
> Maggiori informazioni: <https://manned.org/gdisk>.

- Elenca le partizioni:

`sudo gdisk {{[-l|--list]}}`

- Avvia il manipolatore interattivo di partizioni:

`sudo gdisk {{/dev/sdX}}`

- Apri un menu di aiuto:

`<?>`

- Stampa la tabella delle [p]artizioni:

`<p>`

- Aggiungi una [n]uova partizione:

`<n>`

- Seleziona una partizione da [d]elete:

`<d>`

- [w]write la tabella sul disco ed esci:

`<w>`

- [q]uando senza salvare le modifiche:

`<q>`
