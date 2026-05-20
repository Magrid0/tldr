# sleep

> Ritarda per una quantità di tempo specificata.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/sleep-invocation.html>.

- Ritarda in secondi:

`sleep {{secondi}}`

- Ritarda in [m]inuti (possono essere usate anche altre unità: [d]ay, [h]our, [s]econd, [inf]inity):

`sleep {{minuti}}m`

- Ritarda per 1 [g]iorno e 3 [o]re:

`sleep 1d 3h`

- Esegue un comando specifico dopo un ritardo di 20 [m]inuti:

`sleep 20m && {{comando}}`

- Ritarda all'infinito:

`sleep {{[inf|infinity]}}`

- Mostra aiuto:

`sleep --help`
