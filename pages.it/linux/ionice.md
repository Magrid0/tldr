# ionice

> Ottiene o imposta la classe e la priorità di schedulazione I/O dei programmi.
> Classi di schedulazione: 1 (real-time), 2 (best-effort), 3 (idle).
> Livelli di priorità: 0 (la più alta) - 7 (la più bassa).
> Maggiori informazioni: <https://manned.org/ionice>.

- Esegue un comando con la classe e priorità di schedulazione specificate:

`ionice {{[-c|--class]}} {{scheduling_class}} {{[-n|--classdata]}} {{priority}} {{command}}`

- Imposta la classe di schedulazione I/O di un processo in esecuzione con un [p]id, [P]gid o [u]id specifico:

`ionice {{[-c|--class]}} {{scheduling_class}} -{{p|P|u}} {{id}}`

- Esegue un comando con classe e priorità di schedulazione I/O personalizzate:

`ionice {{[-c|--class]}} {{scheduling_class}} {{[-n|--classdata]}} {{priority}} {{command}}`

- Ignora l'errore nell'impostazione della priorità richiesta:

`ionice {{[-t|--ignore]}} {{[-n|--classdata]}} {{priority}} {{[-p|--pid]}} {{pid}}`

- Esegue il comando anche se non è stato possibile impostare la priorità desiderata (può accadere per privilegi insufficienti o versione del kernel vecchia):

`ionice {{[-t|--ignore]}} {{[-n|--classdata]}} {{priority}} {{[-p|--pid]}} {{pid}}`

- Stampa la classe e la priorità di schedulazione I/O di un processo in esecuzione:

`ionice {{[-p|--pid]}} {{pid}}`
