# setfacl

> Imposta le liste di controllo accesso (ACL) dei file.
> Maggiori informazioni: <https://manned.org/setfacl>.

- Modifica l'ACL di un file per un utente con accesso in lettura e scrittura:

`setfacl {{[-m|--modify]}} u:{{nome_utente}}:rw {{percorso/del/file_o_directory}}`

- Modifica l'ACL predefinita di un file per tutti gli utenti:

`setfacl {{[-d|--default]}} {{[-m|--modify]}} u::rw {{percorso/del/file_o_directory}}`

- Rimuove l'ACL di un file per un utente:

`setfacl {{[-x|--remove]}} u:{{nome_utente}} {{percorso/del/file_o_directory}}`

- Rimuove tutte le voci ACL di un file:

`setfacl {{[-b|--remove-all]}} {{percorso/del/file_o_directory}}`
