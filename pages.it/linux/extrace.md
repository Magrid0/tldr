# extrace

> Traccia le chiamate exec().
> Maggiori informazioni: <https://github.com/leahneukirchen/extrace>.

- Traccia tutte le esecuzioni di programmi che avvengono sul sistema:

`sudo extrace`

- Esegue un comando e traccia solo i discendenti di questo comando:

`sudo extrace {{comando}}`

- Stampa la [d]irectory di lavoro corrente di ogni processo:

`sudo extrace -d`

- Risolve il percorso completo di ogni eseguibile:

`sudo extrace -l`

- Mostra l'[u]tente che esegue ogni processo:

`sudo extrace -u`
