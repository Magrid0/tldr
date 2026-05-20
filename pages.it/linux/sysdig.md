# sysdig

> Risoluzione dei problemi di sistema, analisi ed esplorazione.
> Cattura, filtra e archivia le chiamate di sistema.
> Maggiori informazioni: <https://github.com/draios/sysdig/wiki>.

- Cattura tutti gli eventi dal sistema live e li stampa a schermo:

`sysdig`

- Cattura tutti gli eventi dal sistema live e li salva su disco:

`sysdig {{[-w|--write]}} {{percorso/del/file}}.scap`

- Legge gli eventi da un file e li stampa a schermo:

`sysdig {{[-r|--read]}} {{percorso/del/file}}.scap`

- Filtra e stampa tutte le chiamate di sistema open invocate da cat:

`sysdig proc.name=cat and evt.type=open`

- Registra qualsiasi plugin trovato e usa dummy come fonte di input passando parametri aperti:

`sysdig -I dummy:'{{parametro}}'`

- Elenca i chisel disponibili:

`sysdig {{[-cl|--list-chisels]}}`

- Usa il chisel spy_ip per osservare i dati scambiati con un indirizzo IP:

`sysdig {{[-c|--chisel]}} spy_ip {{indirizzo_ip}}`
