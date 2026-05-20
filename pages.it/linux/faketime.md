# faketime

> Simula l'ora di sistema per un comando.
> Maggiori informazioni: <https://manned.org/faketime>.

- Simula l'ora a questa sera, prima di stampare il risultato di `date`:

`faketime '{{today 23:30}}' {{date}}`

- Apre una nuova shell Bash che utilizza ieri come data corrente:

`faketime '{{yesterday}}' {{bash}}`

- Simula come si comporterebbe un programma venerdì prossimo di notte:

`faketime '{{next Friday 1 am}}' {{path/to/program}}`
