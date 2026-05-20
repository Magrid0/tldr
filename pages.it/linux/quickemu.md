# quickemu

> Crea e gestisci rapidamente macchine virtuali desktop altamente ottimizzate.
> Nota: la macchina virtuale deve essere ferma quando si lavora con gli snapshot.
> Vedi anche: `quickget`.
> Maggiori informazioni: <https://github.com/quickemu-project/quickemu>.

- Crea ed esegue una macchina virtuale da un file di configurazione:

`quickemu --vm {{path/to/file.conf}}`

- Non applica modifiche al disco/snapshot ma scrive le modifiche in file temporanei:

`quickemu --status-quo --vm {{path/to/file.conf}}`

- Avvia la macchina virtuale a schermo intero (`<Ctrl Alt f>` per uscire) e seleziona il backend di visualizzazione (`sdl` di default):

`quickemu --fullscreen --display {{sdl|gtk|spice|spice-app|none}} --vm {{path/to/file.conf}}`

- Seleziona un dispositivo audio virtuale da emulare e crea un collegamento sul desktop:

`quickemu --sound-card {{intel-hda|ac97|es1370|sb16|none}} --shortcut --vm {{path/to/file.conf}}`

- Crea/ripristina/elimina uno snapshot:

`quickemu --snapshot {{create|apply|delete}} {{tag}} --vm {{path/to/file.conf}}`

- Elenca gli snapshot disponibili:

`quickemu --snapshot info --vm {{path/to/file.conf}}`

- Elimina l'intera macchina virtuale e la sua configurazione:

`quickemu --delete-vm --vm {{path/to/file.conf}}`

- Elimina l'immagine disco della macchina virtuale e le variabili EFI:

`quickemu --delete-disk --vm {{path/to/file.conf}}`
