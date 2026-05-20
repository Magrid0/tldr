# lsb_release

> Ottiene informazioni LSB (Linux Standard Base) e specifiche della distribuzione.
> Maggiori informazioni: <https://manned.org/lsb_release>.

- Stampa tutte le informazioni disponibili:

`lsb_release {{[-a|--all]}}`

- Stampa una descrizione (di solito il nome completo) del sistema operativo:

`lsb_release {{[-d|--description]}}`

- Stampa solo il nome del sistema operativo (ID), in formato breve (omettendo il nome del campo):

`lsb_release {{[-is|--id --short]}}`

- Stampa il numero di versione e il nome in codice della distribuzione, in formato breve:

`lsb_release {{[-rcs|--release --codename --short]}}`
