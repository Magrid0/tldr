# smbget

> Utilità simile a `wget` per scaricare file da server SMB.
> Maggiori informazioni: <https://www.samba.org/samba/docs/current/man-html/smbget.1.html>.

- Scarica un file da un server:

`smbget {{smb://server/condivisione/file}}`

- Scarica una condivisione o directory ricorsivamente:

`smbget --recursive {{smb://server/condivisione}}`

- Si connette con un nome utente e una password:

`smbget {{smb://server/condivisione/file}} {{[-U|--user]}} {{nome_utente%password}}`

- Richiede trasferimenti crittografati:

`smbget {{smb://server/condivisione/file}} {{[-e|--encrypt]}}`
