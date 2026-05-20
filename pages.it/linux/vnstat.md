# vnstat

> Un monitor del traffico di rete basato su console.
> Maggiori informazioni: <https://manned.org/vnstat>.

- Mostra il riepilogo del traffico per tutte le interfacce:

`vnstat`

- Mostra il riepilogo del traffico per un'interfaccia di rete specifica:

`vnstat {{[-i|--iface]}} {{interfaccia_rete}}`

- Mostra statistiche in tempo reale per un'interfaccia di rete specifica:

`vnstat {{[-l|--live]}} {{[-i|--iface]}} {{interfaccia_rete}}`

- Mostra le statistiche di traffico su base oraria per le ultime 24 ore usando un grafico a barre:

`vnstat {{[-hg|--hoursgraph]}}`

- Misura e mostra il traffico medio per 30 secondi:

`vnstat {{[-tr|--traffic]}} {{30}}`
