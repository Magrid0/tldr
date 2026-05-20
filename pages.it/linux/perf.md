# perf

> Framework per misurazioni di contatori di prestazioni Linux.
> Maggiori informazioni: <https://perfwiki.github.io/main/>.

- Mostra statistiche base di contatori di prestazioni per un comando:

`perf stat {{gcc hello.c}}`

- Mostra il profilo in tempo reale dei contatori di prestazioni a livello di sistema:

`sudo perf top`

- Esegue un comando e registra il suo profilo in `perf.data`:

`sudo perf record {{comando}}`

- Registra il profilo di un processo esistente in `perf.data`:

`sudo perf record {{[-p|--pid]}} {{pid}}`

- Legge `perf.data` (creato da `perf record`) e mostra il profilo:

`sudo perf report`
