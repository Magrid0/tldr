# ttyplot

> Un'utility di plottaggio in tempo reale per la riga di comando con input dati da `stdin`.
> Maggiori informazioni: <https://github.com/tenox7/ttyplot>.

- Plotta i valori `1`, `2` e `3` (Nota: `cat` impedisce a `ttyplot` di uscire):

`{ echo {{1 2 3}}; cat; } | ttyplot`

- Imposta un titolo e un'unità specifici:

`{ echo {{1 2 3}}; cat; } | ttyplot -t {{titolo}} -u {{unità}}`

- Usa un ciclo while per plottare continuamente valori casuali:

`{ while {{true}}; do echo {{$RANDOM}}; sleep {{1}}; done } | ttyplot`

- Analizza l'output di `ping` e visualizzalo:

`ping {{8.8.8.8}} | sed -u '{{s/^.*time=//g; s/ ms//g}}' | ttyplot -t "{{ping verso 8.8.8.8}}" -u {{ms}}`
