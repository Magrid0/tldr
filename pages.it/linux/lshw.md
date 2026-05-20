# lshw

> Elenca informazioni dettagliate sulle configurazioni hardware come utente root.
> Vedi anche: `inxi`, `hwinfo`, `dmidecode`.
> Maggiori informazioni: <https://ezix.org/project/wiki/HardwareLiSter>.

- Avvia l'interfaccia grafica X11 (se disponibile):

`sudo lshw -X`

- Elenca tutto l'hardware in formato tabellare:

`sudo lshw -short`

- Elenca più classi di hardware (tutti i dischi e i controller di archiviazione) in formato tabellare:

`sudo lshw {{[-c|-class]}} disk {{[-c|-class]}} storage -short`

- Salva tutte le interfacce di rete in un file HTML/XML/JSON:

`sudo lshw {{[-c|-class]}} network -{{html|xml|json}} > interfaces{{.html|.xml|.json}}`

- Elenca le interfacce di rete senza rivelare informazioni sensibili (indirizzi IP, numeri di serie, ecc.):

`sudo lshw {{[-c|-class]}} network -sanitize`

- Elenca una classe particolare di hardware:

`sudo lshw {{[-c|-class]}} {{system|bridge|memory|processor|address|storage|disk|tape|bus|network|display|input|printer|multimedia|communication|power|volume|generic}}`
