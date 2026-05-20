# pactree

> Visualizzatore dell'albero delle dipendenze dei pacchetti per pacman.
> Maggiori informazioni: <https://manned.org/pactree>.

- Mostra l'albero delle dipendenze di un pacchetto specifico:

`pactree {{pacchetto}}`

- Mostra quali pacchetti dipendono da un pacchetto specifico:

`pactree {{[-r|--reverse]}} {{pacchetto}}`

- Mostra le dipendenze una per riga, saltando i duplicati:

`pactree {{[-u|--unique]}} {{pacchetto}}`

- Include le dipendenze opzionali di un pacchetto specifico e colora l'output:

`pactree {{[-co|--color --optional]}} {{pacchetto}}`

- Mostra aiuto:

`pactree`
