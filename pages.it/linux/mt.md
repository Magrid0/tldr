# mt

> Controlla il funzionamento dell'unità a nastro magnetico (comunemente nastro LTO).
> Maggiori informazioni: <https://manned.org/mt>.

- Controlla lo stato di un'unità a nastro:

`mt -f {{/dev/nstX}} status`

- Riavvolge il nastro all'inizio:

`mt -f {{/dev/nstX}} rewind`

- Avanza di un dato numero di file, poi posiziona il nastro sul primo blocco del file successivo:

`mt -f {{/dev/nstX}} fsf {{count}}`

- Riavvolge il nastro, poi posiziona il nastro all'inizio del file specificato:

`mt -f {{/dev/nstX}} asf {{count}}`

- Posiziona il nastro alla fine dei dati validi:

`mt -f {{/dev/nstX}} eod`

- Riavvolge il nastro e lo scarica/espelle:

`mt -f {{/dev/nstX}} eject`

- Scrive un marcatore EOF (End-of-File) alla posizione corrente:

`mt -f {{/dev/nstX}} eof`
