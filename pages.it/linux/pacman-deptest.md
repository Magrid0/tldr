# pacman --deptest

> Controlla ogni dipendenza specificata e restituisce un elenco di dipendenze che non sono attualmente soddisfatte sul sistema.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://manned.org/pacman.8>.

- Stampa i nomi dei pacchetti delle dipendenze che non sono installate:

`pacman -T {{pacchetto1 pacchetto2 ...}}`

- Controlla se il pacchetto installato soddisfa la versione minima data:

`pacman -T "{{bash>=5}}"`

- Controlla se è installata una versione successiva di un pacchetto:

`pacman -T "{{bash>5}}"`

- Mostra [h]elp:

`pacman -Th`
