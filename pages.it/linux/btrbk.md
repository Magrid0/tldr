# btrbk

> Crea snapshot e backup remoti di sottovolumi btrfs.
> Maggiori informazioni: <https://digint.ch/btrbk/doc/readme.html>.

- Stampa statistiche sui sottovolumi e snapshot configurati:

`sudo btrbk stats`

- Elenca i sottovolumi e gli snapshot configurati:

`sudo btrbk list`

- Stampa cosa accadrebbe in un'esecuzione senza apportare le modifiche visualizzate:

`sudo btrbk {{[-v|--verbose]}} dryrun`

- Esegue le routine di backup in modo verboso, mostra la barra di avanzamento:

`sudo btrbk --progress {{[-v|--verbose]}} run`

- Crea solo snapshot per i sottovolumi configurati:

`sudo btrbk snapshot`
