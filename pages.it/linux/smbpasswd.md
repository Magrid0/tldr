# smbpasswd

> Aggiunge/rimuove un utente Samba o cambia la sua password.
> Gli utenti Samba devono avere un account Unix locale esistente.
> Maggiori informazioni: <https://manned.org/smbpasswd.8>.

- Cambia la password SMB dell'utente corrente:

`smbpasswd`

- Aggiunge un utente specificato a Samba e imposta la password (l'utente dovrebbe già esistere nel sistema):

`sudo smbpasswd -a {{nome_utente}}`

- Modifica la password di un utente Samba esistente:

`sudo smbpasswd {{nome_utente}}`

- Elimina un utente Samba (usa `pdbedit` invece se l'account Unix è stato eliminato):

`sudo smbpasswd -x {{nome_utente}}`
