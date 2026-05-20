# eclean

> Pulisce i file sorgente dei repository e i pacchetti binari.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Eclean>.

- Pulisce la directory dei file sorgente:

`sudo eclean distfiles`

- Pulisce la directory dei pacchetti binari:

`sudo eclean packages`

- Pulisce i distfile di tutti i pacchetti disinstallati, ma mantiene i distfile dei pacchetti installati:

`sudo eclean {{[-d|--deep]}} {{[-n|--package-names]}} distfiles`

- Pulisce i pacchetti binari di tutti i pacchetti disinstallati, ma mantiene i binari dei pacchetti installati:

`sudo eclean {{[-d|--deep]}} {{[-n|--package-names]}} packages`
