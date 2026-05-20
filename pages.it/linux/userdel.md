# userdel

> Rimuovi un account utente o rimuovi un utente da un gruppo.
> Vedi anche: `users`, `useradd`, `usermod`.
> Maggiori informazioni: <https://manned.org/userdel>.

- Rimuovi un utente:

`sudo userdel {{nome_utente}}`

- Rimuovi un utente in un'altra directory radice:

`sudo userdel {{[-R|--root]}} {{percorso/dell/altra_root}} {{nome_utente}}`

- Rimuovi un utente insieme alla home directory e al mail spool:

`sudo userdel {{[-r|--remove]}} {{nome_utente}}`
