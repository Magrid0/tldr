# ldconfig

> Configura collegamenti simbolici e cache per le dipendenze delle librerie condivise.
> Maggiori informazioni: <https://manned.org/ldconfig>.

- Aggiorna i collegamenti simbolici e ricostruisce la cache (di solito eseguito quando viene installata una nuova libreria):

`sudo ldconfig`

- Aggiorna i collegamenti simbolici per una directory specifica:

`sudo ldconfig -n {{path/to/directory}}`

- Stampa le librerie nella cache e controlla se una data libreria è presente:

`ldconfig {{[-p|--print-cache]}} | grep {{library_name}}`
