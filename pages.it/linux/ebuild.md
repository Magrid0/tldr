# ebuild

> Un'interfaccia di basso livello al sistema Portage di Gentoo.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Ebuild>.

- Crea o aggiorna il manifest del pacchetto:

`ebuild {{path/to/file.ebuild}} manifest`

- Pulisce le directory di build temporanee per il file di build:

`ebuild {{path/to/file.ebuild}} clean`

- Scarica i sorgenti se non esistono:

`ebuild {{path/to/file.ebuild}} fetch`

- Estrae i sorgenti in una directory di build temporanea:

`ebuild {{path/to/file.ebuild}} unpack`

- Compila i sorgenti estratti:

`ebuild {{path/to/file.ebuild}} compile`

- Installa il pacchetto in una directory di installazione temporanea:

`ebuild {{path/to/file.ebuild}} install`

- Installa i file temporanei nel filesystem live:

`ebuild {{path/to/file.ebuild}} qmerge`

- Scarica, estrae, compila, installa e unisce il file ebuild specificato:

`ebuild {{path/to/file.ebuild}} merge`
