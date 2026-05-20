# dmesg

> Scrive i messaggi del kernel su `stdout`.
> Vedi anche: `journalctl`.
> Maggiori informazioni: <https://manned.org/dmesg>.

- Mostra i messaggi del kernel:

`sudo dmesg`

- Mostra i messaggi di errore del kernel:

`sudo dmesg {{[-l|--level]}} err`

- Mostra i messaggi del kernel e resta in [a]ttesa di nuovi, simile a `tail --follow` (disponibile da kernel 3.5.0 in poi):

`sudo dmesg {{[-w|--follow]}}`

- Mostra quanta memoria fisica è disponibile su questo sistema:

`sudo dmesg | grep {{[-i|--ignore-case]}} memory`

- Mostra i messaggi del kernel una pagina alla volta:

`sudo dmesg | less`

- Mostra i messaggi del kernel con timestamp (disponibile da kernel 3.5.0 in poi):

`sudo dmesg {{[-T|--ctime]}}`

- Mostra i messaggi del kernel in formato leggibile (disponibile da kernel 3.5.0 in poi):

`sudo dmesg {{[-H|--human]}}`

- Colora l'output (disponibile da kernel 3.5.0 in poi):

`sudo dmesg {{[-L|--color]}}`
