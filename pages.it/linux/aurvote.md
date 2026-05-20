# aurvote

> Vota per i pacchetti nell'Arch User Repository.
> Per poter votare, il file `~/.config/aurvote` deve esistere e contenere le tue credenziali AUR.
> Maggiori informazioni: <https://github.com/archlinuxfr/aurvote#name>.

- Crea interattivamente il file `~/.config/aurvote` contenente il tuo nome utente e password AUR:

`aurvote --configure`

- Vota per uno o più pacchetti AUR:

`aurvote {{pacchetto1 pacchetto2 ...}}`

- Annulla il voto per uno o più pacchetti AUR:

`aurvote {{[-u|--unvote]}} {{pacchetto1 pacchetto2 ...}}`

- Controlla se uno o più pacchetti AUR hanno già ricevuto il voto:

`aurvote {{[-c|--check]}} {{pacchetto1 pacchetto2 ...}}`

- Mostra aiuto:

`aurvote {{[-h|--help]}}`
