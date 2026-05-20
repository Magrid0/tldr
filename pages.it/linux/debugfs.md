# debugfs

> Un debugger interattivo per filesystem ext2/ext3/ext4.
> Maggiori informazioni: <https://manned.org/debugfs>.

- Apre il filesystem in modalità sola lettura:

`debugfs {{/dev/sdXN}}`

- Apre il filesystem in modalità lettura e scrittura:

`debugfs -w {{/dev/sdXN}}`

- Legge i comandi da un file specifico, li esegue e poi esce:

`debugfs -f {{path/to/cmd_file}} {{/dev/sdXN}}`

- [Interattivo] Visualizza le statistiche del filesystem nella console debugfs:

`stats`

- [Interattivo] Chiude il filesystem:

`close -a`

- [Interattivo] Elenca tutti i comandi disponibili:

`lr`
