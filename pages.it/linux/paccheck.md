# paccheck

> Controlla i pacchetti installati su un sistema basato su Arch per verificare dipendenze, integrità e consistenza.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/paccheck.pod>.

- Elenca e controlla tutti i pacchetti installati:

`paccheck`

- Controlla i pacchetti specificati:

`paccheck {{pacchetto1 pacchetto2 ...}}`

- Mostra messaggi solo se viene trovato un problema:

`paccheck --quiet`

- Verifica che tutte le dipendenze dei pacchetti siano soddisfatte:

`paccheck --depends`

- Mostra aiuto:

`paccheck --help`

- Mostra versione:

`paccheck --version`
