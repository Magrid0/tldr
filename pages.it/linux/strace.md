# strace

> Strumento di risoluzione dei problemi per tracciare le chiamate di sistema.
> Vedi anche: `fatrace`.
> Maggiori informazioni: <https://manned.org/strace>.

- Avvia il tracciamento di un processo specifico tramite il suo PID:

`sudo strace {{[-p|--attach]}} {{pid}}`

- Traccia un processo e filtra l'output per [e]spressione di chiamata di sistema:

`sudo strace {{[-p|--attach]}} {{pid}} -e {{chiamata_sistema,chiamata_sistema2,...}}`

- Conta tempo, chiamate ed errori per ogni chiamata di sistema e riporta un riepilogo all'uscita del programma:

`sudo strace {{[-p|--attach]}} {{pid}} {{[-c|--summary-only]}}`

- Mostra il tempo speso in ogni chiamata di sistema e specifica la dimensione massima della stringa da stampare:

`sudo strace {{[-p|--attach]}} {{pid}} {{[-T|--syscall-times]}} {{[-s|--string-limit]}} {{32}}`

- Avvia il tracciamento di un programma eseguendolo:

`strace {{programma}}`

- Avvia il tracciamento delle operazioni sui file di un programma:

`strace -e trace=file {{programma}}`

- Avvia il tracciamento delle operazioni di rete di un programma e di tutti i suoi processi figli e forkati, salvando l'output in un file:

`strace {{[-f|--follow-forks]}} -e trace=network {{[-o|--output]}} {{trace.txt}} {{programma}}`
