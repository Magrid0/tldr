# criu

> Congela un'applicazione in esecuzione o un albero di processi e lo ripristina in seguito.
> Maggiori informazioni: <https://manned.org/criu>.

- Verifica se il kernel corrente supporta le funzionalità CRIU necessarie:

`sudo criu check`

- Crea un checkpoint di un processo con un ID specifico, salvando lo stato in una directory specifica:

`sudo criu dump {{[-t|--tree]}} {{process_id}} {{[-D|--images-dir]}} {{path/to/directory}}`

- Ripristina un processo da file immagine salvati in precedenza:

`sudo criu restore {{[-D|--images-dir]}} {{path/to/directory}}`

- Crea un dump di un processo e gli permette di continuare a essere eseguito invece di terminarlo:

`sudo criu dump {{[-t|--tree]}} {{process_id}} {{[-D|--images-dir]}} {{path/to/directory}} {{[-R|--leave-running]}}`
