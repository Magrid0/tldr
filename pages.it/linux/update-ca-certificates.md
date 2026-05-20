# update-ca-certificates

> Aggiorna il bundle dei certificati CA e rigenera `/etc/ssl/certs`.
> Maggiori informazioni: <https://manned.org/update-ca-certificates>.

- Aggiorna i certificati:

`sudo update-ca-certificates`

- Aggiorna i certificati in modalità verbosa:

`sudo update-ca-certificates {{[-v|--verbose]}}`

- Esegui un aggiornamento completo (rimuovi tutti i collegamenti simbolici e rigenera):

`sudo update-ca-certificates {{[-f|--fresh]}}`

- Aggiungi un certificato personalizzato (prima copialo, poi aggiorna):

`sudo cp {{percorso/del/certificato.crt}} /usr/local/share/ca-certificates/ && sudo update-ca-certificates`
