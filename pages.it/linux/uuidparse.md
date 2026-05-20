# uuidparse

> Analizza identificatori universali univoci.
> Vedi anche: `uuidgen`.
> Maggiori informazioni: <https://manned.org/uuidparse>.

- Analizza gli UUID specificati, usando un formato di output tabellare:

`uuidparse {{uuid1 uuid2 ...}}`

- Analizza UUID da `stdin`:

`{{comando}} | uuidparse`

- Usa il formato di output JSON:

`uuidparse {{[-J|--json]}} {{uuid1 uuid2 ...}}`

- Non stampare una riga di intestazione:

`uuidparse {{[-n|--noheadings]}} {{uuid1 uuid2 ...}}`

- Usa il formato di output raw:

`uuidparse {{[-r|--raw]}} {{uuid1 uuid2 ...}}`

- Specifica quali delle quattro colonne di output stampare:

`uuidparse {{[-o|--output]}} {{UUID,VARIANT,TYPE,TIME}}`

- Mostra aiuto:

`uuidparse {{[-h|--help]}}`
