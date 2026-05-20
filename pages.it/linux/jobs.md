# jobs

> Shell builtin per visualizzare informazioni sui processi avviati dalla shell corrente.
> Le opzioni diverse da `-l` e `-p` sono esclusive di Bash.
> Vedi anche: `fg`, `bg`, `disown`, `%`.
> Maggiori informazioni: <https://www.gnu.org/software/bash/manual/bash.html#index-jobs>.

- Visualizza i job avviati dalla shell corrente:

`jobs`

- Elenca i job e i loro ID di processo:

`jobs -l`

- Mostra informazioni sui job con stato modificato:

`jobs -n`

- Mostra solo gli ID di processo:

`jobs -p`

- Mostra i processi in esecuzione:

`jobs -r`

- Mostra i processi fermati:

`jobs -s`
