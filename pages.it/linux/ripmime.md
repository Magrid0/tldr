# ripmime

> Estrae gli allegati da un pacchetto email codificato MIME.
> Maggiori informazioni: <https://pldaniels.com/ripmime/>.

- Estrae il contenuto del file nella directory corrente:

`ripmime -i {{path/to/file}}`

- Estrae il contenuto del file in una directory specifica:

`ripmime -i {{path/to/file}} -d {{path/to/directory}}`

- Estrae il contenuto del file e stampa output verboso:

`ripmime -i {{path/to/file}} -v`

- Ottiene informazioni dettagliate sull'intero processo di decodifica:

`ripmime -i {{path/to/file}} --debug`
