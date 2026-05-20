# semanage-login

> Gestisce le mappature di login SELinux tra utenti Linux e utenti SELinux.
> Vedi anche: `semanage`, `semanage-user`.
> Maggiori informazioni: <https://manned.org/semanage-login>.

- Elenca tutte le mappature di login:

`sudo semanage login {{[-l|--list]}}`

- Aggiunge una mappatura di login (mappa utente Linux a utente SELinux):

`sudo semanage login {{[-a|--add]}} {{[-s|--seuser]}} {{utente_selinux}} {{nome_utente_linux}}`

- Elimina una mappatura di login:

`sudo semanage login {{[-d|--delete]}} {{nome_utente_linux}}`

- Modifica una mappatura di login esistente:

`sudo semanage login {{[-m|--modify]}} {{[-s|--seuser]}} {{utente_selinux}} {{nome_utente_linux}}`

- Aggiunge una mappatura di login con un intervallo MLS/MCS specifico:

`sudo semanage login {{[-a|--add]}} {{[-s|--seuser]}} {{user_u}} {{[-r|--range]}} {{s0-s0:c0.c1023}} {{nome_utente_linux}}`

- Elenca solo le mappature di login personalizzate:

`sudo semanage login {{[-l|--list]}} {{[-C|--locallist]}}`
