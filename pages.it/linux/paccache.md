# paccache

> Un'utilità per la pulizia della cache di `pacman`.
> Maggiori informazioni: <https://manned.org/paccache>.

- Rimuovi tutte le versioni dei pacchetti dal cache di `pacman` eccetto le 3 più recenti:

`paccache {{[-r|--remove]}}`

- Imposta il numero di versioni dei pacchetti da conservare:

`paccache {{[-rk|--remove --keep]}} {{num_versioni}}`

- Esegui una simulazione e mostra il numero di pacchetti candidati per l'eliminazione:

`paccache {{[-d|--dryrun]}}`

- Sposta i pacchetti candidati in una directory invece di eliminarli:

`paccache {{[-m|--move]}} {{percorso/della/directory}}`
