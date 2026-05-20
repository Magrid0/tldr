# pacman --upgrade

> Installa pacchetti manualmente da file di archivio.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://manned.org/pacman.8>.

- Installa uno o più pacchetti da file:

`sudo pacman -U {{percorso/del/pacchetto1.pkg.tar.zst percorso/del/pacchetto2.pkg.tar.zst ...}}`

- Installa un pacchetto senza chiedere conferma:

`sudo pacman -U --noconfirm {{percorso/del/pacchetto.pkg.tar.zst}}`

- Sovrascrive i file in conflitto durante l'installazione:

`sudo pacman -U --overwrite {{percorso/del/file}} {{percorso/del/pacchetto.pkg.tar.zst}}`

- Installa un pacchetto, saltando i controlli di versione delle [d]ipendenze:

`sudo pacman -Ud {{percorso/del/pacchetto.pkg.tar.zst}}`

- Scarica e [s]tampa i pacchetti che sarebbero interessati dall'aggiornamento (non installa alcun pacchetto):

`pacman -Up {{percorso/del/pacchetto.pkg.tar.zst}}`

- Mostra [h]elp:

`pacman -Uh`
