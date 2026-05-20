# semanage fcontext

> Gestisce le regole di contesto di sicurezza persistenti di SELinux su file/directory.
> Vedi anche: `semanage`, `matchpathcon`, `secon`, `chcon`, `restorecon`.
> Maggiori informazioni: <https://manned.org/semanage-fcontext>.

- Elenca tutte le regole di etichettatura dei file:

`sudo semanage fcontext {{[-l|--list]}}`

- Elenca tutte le regole di etichettatura dei file definite dall'utente senza intestazioni:

`sudo semanage fcontext {{[-lCn|--list --locallist --noheading]}}`

- Aggiunge una regola definita dall'utente che etichetta qualsiasi percorso che corrisponde a un PCRE `regex`:

`sudo semanage fcontext {{[-a|--add]}} {{[-t|--type]}} {{samba_share_t}} '{{/mnt/share(/.*)?}}'`

- Aggiunge una regola definita dall'utente che crea un'equivalenza di etichettatura tra due sottopercorsi:

`sudo semanage fcontext {{[-a|--add]}} {{[-e|--equal]}} /{{percorso/del/ref}} /{{percorso/del/destinazione}}`

- Elimina una regola definita dall'utente usando il suo PCRE `regex`:

`sudo semanage fcontext {{[-d|--delete]}} '{{/mnt/share(/.*)?}}'`

- Ricarica una directory ricorsivamente applicando le nuove regole:

`restorecon -Rv {{percorso/della/directory}}`
