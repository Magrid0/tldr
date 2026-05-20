# nerdctl

> CLI compatibile con Docker per containerd.
> Maggiori informazioni: <https://github.com/containerd/nerdctl/blob/main/docs/command-reference.md>.

- Elenca tutti i container (in esecuzione e arrestati):

`nerdctl ps {{[-a|--all]}}`

- Avvia un container da un'immagine, con un nome personalizzato:

`nerdctl run --name {{nome_container}} {{immagine}}`

- Avvia o arresta un container esistente:

`nerdctl {{start|stop}} {{nome_container}}`

- Scarica un'immagine da un registro container:

`nerdctl pull {{immagine}}`

- Mostra l'elenco delle immagini già scaricate:

`nerdctl images`

- Apre una tty interattiva con Bourne shell (`sh`) all'interno di un container in esecuzione:

`nerdctl exec {{[-it|--interactive --tty]}} {{nome_container}} sh`

- Rimuove i container arrestati:

`nerdctl rm {{container1 container2 ...}}`

- Recupera e segue i log di un container:

`nerdctl logs {{[-f|--follow]}} {{nome_container}}`
