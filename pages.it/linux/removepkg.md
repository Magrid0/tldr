# removepkg

> Rimuove un pacchetto Slackware specificato.
> Maggiori informazioni: <https://www.slackbook.org/html/book.html#PACKAGE-MANAGEMENT-PACKAGE-UTILITIES-REMOVEPKG>.

- Rimuove un pacchetto:

`sudo removepkg {{package_name}}`

- Genera un report di una rimozione simulata su `stdout`:

`removepkg -warn {{package_name}}`

- Ricostruisce il sottoalbero del pacchetto in `/tmp/preserved_packages/package_name` e rimuove il pacchetto:

`sudo removepkg -preserve {{package_name}}`

- Copia il pacchetto in `/tmp/preserved_packages/package_name` senza rimuoverlo:

`removepkg -copy {{package_name}}`

- Salva i file temporanei creati da `removepkg` per il debug:

`sudo removepkg -keep {{package_name}}`
