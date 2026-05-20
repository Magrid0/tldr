# lftp

> Programma di trasferimento file sofisticato.
> Maggiori informazioni: <https://lftp.yar.ru/lftp-man.html>.

- Si connette a un server FTP:

`lftp {{[-u|--user]}} {{username}} {{ftp.example.com}}`

- [Interattivo] Scarica più file (espressione glob):

`mget {{path/to/*.png}}`

- [Interattivo] Carica più file (espressione glob):

`mput {{path/to/*.zip}}`

- [Interattivo] Elimina più file sul server remoto:

`mrm {{path/to/*.txt}}`

- [Interattivo] Rinomina un file sul server remoto:

`mv {{original_filename}} {{new_filename}}`

- [Interattivo] Scarica o aggiorna un'intera directory:

`mirror {{path/to/remote_directory}} {{path/to/local_output_directory}}`

- [Interattivo] Carica o aggiorna un'intera directory:

`mirror {{[-R|--reverse]}} {{path/to/local_directory}} {{path/to/remote_output_directory}}`
