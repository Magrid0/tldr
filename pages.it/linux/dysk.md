# dysk

> Mostra le informazioni del filesystem in una tabella.
> Maggiori informazioni: <https://manned.org/dysk>.

- Ottiene una panoramica standard dei tuoi dischi abituali:

`dysk`

- Ordina per spazio libero:

`dysk {{[-s|--sort]}} free`

- Includi solo dischi HDD:

`dysk {{[-f|--filter]}} 'disk = HDD'`

- Escludi dischi SSD:

`dysk {{[-f|--filter]}} 'disk <> SSD'`

- Mostra i dischi con alta utilizzazione o poco spazio libero:

`dysk {{[-f|--filter]}} 'use > 65% | free < 50G'`
