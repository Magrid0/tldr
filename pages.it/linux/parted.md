# parted

> Programma per la manipolazione delle partizioni.
> Vedi anche: `parted.interactive`, `cfdisk`, `partprobe`.
> Maggiori informazioni: <https://www.gnu.org/software/parted/manual/parted.html#Invoking-Parted>.

- Elenca le partizioni su tutti i dispositivi a blocchi:

`sudo parted {{[-l|--list]}}`

- Crea una nuova tabella delle partizioni del tipo di etichetta specificato:

`sudo parted {{/dev/sdX}} mklabel {{aix|amiga|bsd|dvh|gpt|loop|mac|msdos|pc98|sun}}`

- Crea una nuova tabella partizioni `gpt` con una partizione di boot da 500MiB e assegna il resto per la partizione di sistema (`--script` salta le richieste di intervento dell'utente):

`sudo parted {{/dev/sdX}} {{[-s|--script]}} mklabel gpt mkpart "{{nome_partizione_boot}}" 0% 500MiB mkpart "{{nome_partizione_sistema}}" 500MiB 100%`

- Imposta il flag di boot su una partizione:

`sudo parted {{/dev/sdX}} set {{1}} boot on`

- Avvia la modalità interattiva con il disco specificato selezionato:

`sudo parted {{/dev/sdX}}`

- Mostra aiuto:

`parted {{[-h|--help]}}`
