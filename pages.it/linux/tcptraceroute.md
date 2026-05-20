# tcptraceroute

> Implementazione di traceroute che utilizza pacchetti TCP.
> Maggiori informazioni: <https://manned.org/tcptraceroute>.

- Traccia la rotta verso un host:

`tcptraceroute {{host}}`

- Specifica la porta di destinazione e la lunghezza del pacchetto in byte:

`tcptraceroute {{host}} {{porta_destinazione}} {{lunghezza_pacchetto}}`

- Specifica la porta sorgente locale e l'indirizzo sorgente:

`tcptraceroute {{host}} -p {{porta_sorgente}} -s {{indirizzo_sorgente}}`

- Imposta il primo e il massimo TTL:

`tcptraceroute {{host}} -f {{primo_ttl}} -m {{max_ttl}}`

- Specifica il tempo di attesa e il numero di query per hop:

`tcptraceroute {{host}} -w {{tempo_attesa}} -q {{numero_query}}`

- Specifica l'interfaccia:

`tcptraceroute {{host}} -i {{interfaccia}}`
