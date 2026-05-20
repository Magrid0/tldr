# exec

> Esegue un comando senza creare un processo figlio.
> Maggiori informazioni: <https://www.gnu.org/software/bash/manual/bash.html#index-exec>.

- Esegue un comando specifico:

`exec {{comando -con -flag}}`

- Esegue un comando con un ambiente (per lo più) vuoto:

`exec -c {{comando -con -flag}}`

- Esegue un comando come shell di login:

`exec -l {{comando -con -flag}}`

- Esegue un comando con un nome diverso:

`exec -a {{nome}} {{comando -con -flag}}`
