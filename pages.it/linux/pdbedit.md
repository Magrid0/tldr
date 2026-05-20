# pdbedit

> Modifica il database utenti di Samba.
> Per semplici aggiunte/rimozioni/password utente, puoi anche usare `smbpasswd`.
> Maggiori informazioni: <https://manned.org/pdbedit>.

- Elenca tutti gli utenti Samba:

`sudo pdbedit {{[-L|--list]}}`

- Elenca tutti gli utenti Samba e le loro impostazioni:

`sudo pdbedit {{[-L|--list]}} {{[-v|--verbose]}}`

- Aggiungi un utente Unix esistente a Samba (richiederà la password):

`sudo pdbedit {{[-u|--user]}} {{nome_utente}} {{[-a|--create]}}`

- Rimuovi un utente Samba:

`sudo pdbedit {{[-u|--user]}} {{nome_utente}} {{[-x|--delete]}}`

- Reimposta il contatore di password fallite di un utente Samba:

`sudo pdbedit {{[-u|--user]}} {{nome_utente}} {{[-z|--bad-password-count-reset]}}`
