# Palworld

> Crea e avvia un server Palworld headless.
> Maggiori informazioni: <https://docs.palworldgame.com/settings-and-operation/arguments/>.

- Avvia il server con le impostazioni predefinite:

`{{percorso}}/PalServer.sh`

- Avvia il server con una porta specifica e imposta un numero massimo di giocatori:

`{{percorso}}/PalServer.sh -port={{8211}} -players={{1..32}}`

- Avvia un server lobby pubblico:

`{{percorso}}/PalServer.sh -publiclobby`

- Avvia il server con ottimizzazioni per CPU multi-thread:

`{{percorso}}/PalServer.sh -useperfthreads -NoAsyncLoadingThread -UseMultithreadForDS`

- Avvia il server con un IP pubblico e una porta specifici per server community:

`{{percorso}}/PalServer.sh -publicip={{indirizzo_ip}} -publicport={{porta}}`
