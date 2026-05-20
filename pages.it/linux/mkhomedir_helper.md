# mkhomedir_helper

> Crea la home directory dell'utente dopo aver creato l'utente.
> Maggiori informazioni: <https://manned.org/mkhomedir_helper>.

- Crea una home directory per un utente basata su `/etc/skel` con umask 022:

`sudo mkhomedir_helper {{username}}`

- Crea una home directory per un utente basata su `/etc/skel` con tutti i permessi per il proprietario (0) e permesso di lettura per il gruppo (3):

`sudo mkhomedir_helper {{username}} {{037}}`

- Crea una home directory per un utente basata su uno scheletro personalizzato:

`sudo mkhomedir_helper {{username}} {{umask}} {{path/to/skeleton_directory}}`
