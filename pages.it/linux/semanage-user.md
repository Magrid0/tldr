# semanage-user

> Gestisce le mappature degli utenti SELinux.
> Vedi anche: `semanage`, `semanage-login`.
> Maggiori informazioni: <https://manned.org/semanage-user>.

- Elenca tutti gli utenti SELinux:

`sudo semanage user {{[-l|--list]}}`

- Aggiunge un nuovo utente SELinux:

`sudo semanage user {{[-a|--add]}} {{[-R|--roles]}} {{nome_ruolo}} {{utente_selinux}}`

- Elimina un utente SELinux:

`sudo semanage user {{[-d|--delete]}} {{utente_selinux}}`

- Modifica i ruoli di un utente SELinux esistente:

`sudo semanage user {{[-m|--modify]}} {{[-R|--roles]}} {{nome_ruolo}} {{utente_selinux}}`

- Aggiunge un utente SELinux con un livello predefinito specifico:

`sudo semanage user {{[-a|--add]}} {{[-R|--roles]}} {{nome_ruolo}} {{[-L|--level]}} {{s0}} {{utente_selinux}}`

- Aggiunge un utente SELinux con un intervallo MLS/MCS specifico:

`sudo semanage user {{[-a|--add]}} {{[-R|--roles]}} {{nome_ruolo}} {{[-r|--range]}} {{s0-s0:c0.c1023}} {{utente_selinux}}`

- Elenca solo gli utenti SELinux personalizzati:

`sudo semanage user {{[-l|--list]}} {{[-C|--locallist]}}`
