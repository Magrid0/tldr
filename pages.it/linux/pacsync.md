# pacsync

> Aggiorna i database di sincronizzazione.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/pacsync.pod>.

- Aggiorna tutti i database di sincronizzazione:

`sudo pacsync`

- Aggiorna database di sincronizzazione specifici:

`sudo pacsync {{repository1 repository2 ...}}`

- Aggiorna i database di sincronizzazione anche se già aggiornati:

`sudo pacsync --force`

- Aggiorna i database di sincronizzazione usando un file di configurazione specifico:

`sudo pacsync --config {{percorso/pacman.conf}}`

- Aggiorna i database di sincronizzazione e restituisce true solo se un database è stato effettivamente aggiornato:

`sudo pacsync --updated`
