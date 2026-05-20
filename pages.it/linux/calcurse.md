# calcurse

> Un'applicazione testuale per calendario e pianificazione.
> Maggiori informazioni: <https://github.com/lfos/calcurse/blob/pu/doc/calcurse.1.txt>.

- Avvia `calcurse` in modalità interattiva:

`calcurse`

- Stampa gli appuntamenti e gli eventi per il giorno corrente ed esce:

`calcurse {{[-a|--appointment]}}`

- Rimuove tutti gli elementi locali di calcurse e importa oggetti remoti:

`calcurse-caldav --init=keep-remote`

- Rimuove tutti gli oggetti remoti e invia gli elementi locali di calcurse:

`calcurse-caldav --init=keep-local`

- Copia gli oggetti locali sul server CalDAV e viceversa:

`calcurse-caldav --init=two-way`
