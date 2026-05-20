# debchange

> Gestisce il file debian/changelog di un pacchetto sorgente Debian.
> Maggiori informazioni: <https://manned.org/debchange>.

- Aggiunge una nuova versione per un upload non mantenitore al changelog:

`debchange {{[-n|--nmu]}}`

- Aggiunge una voce di changelog alla versione corrente:

`debchange {{[-a|--append]}}`

- Aggiunge una voce di changelog per chiudere il bug con l'ID specificato:

`debchange --closes {{bug_id}}`
