# dm-tool

> Uno strumento per comunicare con il display manager.
> Maggiori informazioni: <https://manned.org/dm-tool>.

- Mostra il greeter mantenendo aperta la sessione desktop corrente e attendendo di essere ripristinato dopo l'autenticazione dell'utente:

`dm-tool switch-to-greeter`

- Blocca la sessione corrente:

`dm-tool lock`

- Passa a un utente specifico, mostrando una richiesta di autenticazione se necessaria:

`dm-tool switch-to-user {{username}} {{session}}`

- Aggiunge un seggio dinamico da una sessione LightDM in esecuzione:

`dm-tool add-seat {{xlocal}} {{name}}={{value}}`
