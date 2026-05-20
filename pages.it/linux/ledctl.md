# ledctl

> Applicazione di controllo LED Intel(R) Enclosure.
> Maggiori informazioni: <https://manned.org/ledctl>.

- Accende il LED "Locate" per i dispositivi specificati:

`sudo ledctl locate={{/dev/sda,/dev/sdb,...}}`

- Spegne il LED "Locate" per i dispositivi specificati:

`sudo ledctl locate_off={{/dev/sda,/dev/sdb,...}}`

- Spegne il LED "Status" e il LED "Failure" per i dispositivi specificati:

`sudo ledctl off={{/dev/sda,/dev/sdb,...}}`

- Spegne il LED "Status", il LED "Failure" e il LED "Locate" per i dispositivi specificati:

`sudo ledctl normal={{/dev/sda,/dev/sdb,...}}`
