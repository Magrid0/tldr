# quickget

> Scarica e prepara il materiale per creare una macchina virtuale Quickemu.
> Nota: il parametro "edition" è talvolta opzionale.
> Vedi anche: `quickemu`.
> Maggiori informazioni: <https://github.com/quickemu-project/quickemu>.

- Mostra l'elenco di tutti i sistemi operativi guest supportati, versioni e varianti in vari formati:

`quickget {{--list|--list-csv|--list-json}}`

- Scarica e crea la configurazione della macchina virtuale per creare una VM Quickemu per un sistema operativo:

`quickget {{os}} {{release}} {{edition}}`

- Scarica la configurazione per una VM Windows 11 con driver VirtIO per Windows:

`quickget windows 11`

- Scarica un'immagine di ripristino macOS e crea una configurazione della macchina virtuale:

`quickget macos {{mojave|catalina|big-sur|monterey|ventura|sonoma}}`

- Mostra un URL ISO per un sistema operativo:

`quickget --url {{os}} {{release}} {{edition}}`

- Verifica se un file ISO è disponibile per un sistema operativo:

`quickget --check {{os}} {{release}} {{edition}}`

- Scarica un'immagine senza creare alcuna configurazione VM:

`quickget --download {{os}} {{release}} {{edition}}`

- Crea una configurazione VM per un'immagine del sistema operativo (questo sposterà l'ISO dalla directory di origine):

`quickget --create-config {{os}} {{path/to/iso}}`
