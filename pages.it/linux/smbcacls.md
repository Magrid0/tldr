# smbcacls

> Visualizza e manipola ACL Windows su condivisioni SMB.
> Parte della suite Samba.
> Maggiori informazioni: <https://www.samba.org/samba/docs/current/man-html/smbcacls.1.html>.

- Mostra gli ACL per un file o directory su una condivisione SMB remota:

`smbcacls //{{server}}/{{condivisione}} {{percorso/del/file_o_directory}} --user {{dominio\\nome_utente}}%{{password}}`

- Imposta un nuovo ACL per un file su una condivisione SMB remota (sostituisci `"ACL:..."` con una specifica ACL Windows valida):

`smbcacls //{{server}}/{{condivisione}} {{percorso/del/file}} --user {{dominio\\nome_utente}}%{{password}} "ACL:{{DACL}}"`

- Rimuove tutte le voci ACL esistenti e imposta un nuovo ACL:

`smbcacls //{{server}}/{{condivisione}} {{percorso/del/file}} --user {{dominio\\nome_utente}}%{{password}} "RESET" "ACL:{{DACL}}"`

- Specifica un workgroup (o dominio) alternativo e fa sì che il programma richieda una password in modo interattivo:

`smbcacls //{{server}}/{{condivisione}} {{percorso/del/file}} --user {{nome_utente}} --workgroup {{workgroup}}`
