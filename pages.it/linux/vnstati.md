# vnstati

> Supporto per output di immagini PNG per vnStat.
> Maggiori informazioni: <https://manned.org/vnstati>.

- Output di un riepilogo degli ultimi 2 mesi, giorni e totali:

`vnstati --summary --iface {{interfaccia_rete}} --output {{percorso/dell/output.png}}`

- Output dei 10 giorni con più traffico di tutti i tempi:

`vnstati --top 10 --iface {{interfaccia_rete}} --output {{percorso/dell/output.png}}`

- Output delle statistiche di traffico mensili degli ultimi 12 mesi:

`vnstati --months --iface {{interfaccia_rete}} --output {{percorso/dell/output.png}}`

- Output delle statistiche di traffico orarie delle ultime 24 ore:

`vnstati --hours --iface {{interfaccia_rete}} --output {{percorso/dell/output.png}}`
