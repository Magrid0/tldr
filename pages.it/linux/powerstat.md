# powerstat

> Misura il consumo energetico di un computer che ha una batteria o supporta l'interfaccia RAPL.
> Maggiori informazioni: <https://manned.org/powerstat>.

- Misura il consumo con 10 campioni predefiniti a intervallo di 10 secondi:

`powerstat`

- Misura il consumo con numero personalizzato di campioni e durata dell'intervallo:

`powerstat {{intervallo}} {{numero_campioni}}`

- Misura il consumo usando l'interfaccia RAPL di Intel:

`powerstat -R {{intervallo}} {{numero_campioni}}`

- Mostra un istogramma delle misurazioni di consumo:

`powerstat -H {{intervallo}} {{numero_campioni}}`

- Abilita tutte le opzioni di raccolta statistiche:

`powerstat -a {{intervallo}} {{numero_campioni}}`
