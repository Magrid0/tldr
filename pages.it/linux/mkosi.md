# mkosi

> Costruisce immagini Linux moderne e senza legacy.
> Parte di `systemd`.
> Maggiori informazioni: <https://manned.org/mkosi>.

- Mostra la configurazione di build corrente per verificare cosa verrebbe costruito:

`mkosi summary`

- Costruisce un'immagine con le impostazioni predefinite (se non viene selezionata alcuna distribuzione, viene usata quella del sistema host):

`mkosi build --distribution {{fedora|debian|ubuntu|arch|opensuse|...}}`

- Costruisce un'immagine e avvia una shell interattiva in un container systemd-nspawn dell'immagine:

`mkosi shell`

- Avvia un'immagine in una macchina virtuale usando QEMU (supportato solo per immagini disco o immagini CPIO quando viene fornito un kernel):

`mkosi qemu`

- Mostra aiuto:

`mkosi help`
