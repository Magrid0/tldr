# pacman --sync

> Sincronizza pacchetti da repository remoti.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://manned.org/pacman.8>.

- Installa un nuovo pacchetto:

`sudo pacman -S {{pacchetto}}`

- [S]incronizza e aggiorna ([y]) il database dei pacchetti insieme a un sys[u]pgrade di sistema (aggiungi `--downloadonly` per solo scaricare i pacchetti e non installarli):

`sudo pacman -Syu`

- Aggiorna e [u]pgrade tutti i pacchetti e installane uno nuovo senza chiedere conferma:

`sudo pacman -Syu --noconfirm {{pacchetto}}`

- [s]earch nel database dei pacchetti una `regex` o parola chiave:

`pacman -Ss "{{pattern_ricerca}}"`

- Mostra [i]nformazioni su un pacchetto:

`pacman -Si {{pacchetto}}`

- Sovrascrive i file in conflitto durante un aggiornamento:

`sudo pacman -Syu --overwrite {{percorso/del/file}}`

- Rimuovi i pacchetti non installati e i repository inutilizzati dalla cache (usa il flag `Scc` per [c]ancellare tutti i pacchetti):

`sudo pacman -Sc`

- Specifica la versione del pacchetto da installare:

`sudo pacman -S {{pacchetto}}={{versione}}`
