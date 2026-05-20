# lscpu

> Mostra informazioni sull'architettura della CPU.
> Maggiori informazioni: <https://manned.org/lscpu>.

- Mostra informazioni su tutte le CPU:

`lscpu`

- Mostra informazioni in una tabella:

`lscpu {{[-e|--extended]}}`

- Mostra solo informazioni sulle CPU online in una tabella:

`lscpu {{[-e|--extended]}} {{[-b|--online]}}`

- Mostra solo informazioni sulle CPU offline in una tabella:

`lscpu {{[-e|--extended]}} {{[-c|--offline]}}`

- Mostra dettagli sulle cache della CPU:

`lscpu {{[-C|--caches]}}`

- Mostra informazioni in formato JSON:

`lscpu {{[-J|--json]}}`
