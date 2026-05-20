# pacman-key

> Script wrapper per GnuPG usato per gestire il portachiavi di pacman.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://manned.org/pacman-key>.

- Inizializza il portachiavi di `pacman`:

`sudo pacman-key --init`

- Aggiunge le chiavi predefinite di Arch Linux:

`sudo pacman-key --populate`

- Elenca le chiavi dal portachiavi pubblico:

`pacman-key {{[-l|--list-keys]}}`

- Aggiunge le chiavi specificate:

`sudo pacman-key {{[-a|--add]}} {{percorso/del/file_chiave.gpg}}`

- Riceve una chiave da un server di chiavi:

`sudo pacman-key {{[-r|--recv-keys]}} "{{uid|nome|email}}"`

- Stampa l'impronta digitale di una chiave specifica:

`pacman-key {{[-f|--finger]}} "{{uid|nome|email}}"`

- Firma localmente una chiave importata:

`sudo pacman-key --lsign-key "{{uid|nome|email}}"`

- Rimuove una chiave specifica:

`sudo pacman-key {{[-d|--delete]}} "{{uid|nome|email}}"`
