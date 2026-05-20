# chattr

> Modifica gli attributi di file o directory.
> Maggiori informazioni: <https://manned.org/chattr>.

- Rende un file o una directory [i]mmutabile a modifiche ed eliminazione, anche da parte del superutente:

`sudo chattr +i {{path/to/file_or_directory}}`

- Rende un file o una directory mutabile:

`sudo chattr -i {{path/to/file_or_directory}}`

- [R]ende ricorsivamente un'intera directory e il suo contenuto immutabili:

`sudo chattr -R +i {{path/to/directory}}`

- Marca una directory e i suoi file per essere interpretati senza distinzione tra maiuscole e minuscole (case-[F]olding):

`chattr +F {{path/to/directory}}`

- Imposta un file per consentire solo l'[a]ggiunta in coda:

`sudo chattr +a {{path/to/file}}`
