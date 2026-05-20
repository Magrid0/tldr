# findfs

> Trova un filesystem tramite etichetta o UUID.
> Maggiori informazioni: <https://manned.org/findfs>.

- Cerca dispositivi a blocchi tramite etichetta del filesystem:

`findfs LABEL={{label}}`

- Cerca tramite UUID del filesystem:

`findfs UUID={{uuid}}`

- Cerca tramite etichetta della partizione (tabella delle partizioni GPT o MAC):

`findfs PARTLABEL={{partition_label}}`

- Cerca tramite UUID della partizione (solo tabella delle partizioni GPT):

`findfs PARTUUID={{partition_uuid}}`
