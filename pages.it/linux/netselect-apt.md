# netselect-apt

> Crea un file `sources.list` per un mirror Debian con la latenza più bassa.
> Maggiori informazioni: <https://manned.org/netselect-apt>.

- Crea `sources.list` usando il server con la latenza più bassa:

`sudo netselect-apt`

- Specifica il ramo Debian, stable è usato per impostazione predefinita:

`sudo netselect-apt {{testing}}`

- Include la sezione non-free:

`sudo netselect-apt {{[-n|--non-free]}}`

- Specifica un paese per la ricerca dell'elenco dei mirror:

`sudo netselect-apt {{[-c|--country]}} {{Italia}}`
