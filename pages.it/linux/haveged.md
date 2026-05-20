# haveged

> Generatore di numeri casuali basato su hardware.
> Maggiori informazioni: <https://manned.org/haveged>.

- Genera un numero casuale:

`sudo haveged`

- Esegue `haveged` in primo piano:

`sudo haveged {{[-F|--Foreground]}}`

- Imposta il percorso del file per l'output di `haveged`:

`sudo haveged {{[-f|--file]}} {{path/to/file}}`

- Imposta il livello di esecuzione per il demone:

`sudo haveged {{[-r|--run]}} {{runlevel}}`

- Imposta la dimensione del buffer di raccolta in parole di kibibyte:

`sudo haveged {{[-b|--buffer]}} {{buffersizeinKW}}`

- Inserisce un comando in un processo o demone `haveged` già in esecuzione:

`sudo haveged {{[-c|--command]}} {{command}}`

- Imposta la dimensione della cache in parole di kibibyte:

`sudo haveged {{[-d|--data]}} {{cachesizeinKW}}`

- Imposta il numero di byte da scrivere nel file di output:

`sudo haveged {{[-n|--number]}} {{byteamount}}`
