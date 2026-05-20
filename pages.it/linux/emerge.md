# emerge

> Utilità di gestione dei pacchetti di Gentoo Linux.
> Per comandi equivalenti in altri gestori di pacchetti, vedere <https://wiki.archlinux.org/title/Pacman/Rosetta>.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Portage#emerge>.

- Sincronizza tutti i pacchetti:

`sudo emerge --sync`

- Aggiorna tutti i pacchetti, incluse le dipendenze:

`sudo emerge {{[-avuDN|--ask --verbose --update --deep --newuse]}} @world`

- Riprende un aggiornamento fallito, saltando il pacchetto che ha causato l'errore:

`sudo emerge --resume --skipfirst`

- Installa un nuovo pacchetto, con conferma:

`sudo emerge {{[-av|--ask --verbose]}} {{pacchetto}}`

- Rimuove un pacchetto e le sue dipendenze con conferma:

`sudo emerge {{[-avc|--ask --verbose --depclean]}} {{pacchetto}}`

- Rimuove i pacchetti orfani (installati come dipendenze ma non più richiesti da alcun pacchetto):

`sudo emerge {{[-avc|--ask --verbose --depclean]}}`

- Cerca nel database dei pacchetti una parola chiave:

`emerge {{[-S|--searchdesc]}} {{parola_chiave}}`
