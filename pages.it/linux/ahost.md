# ahost

> Utility di lookup DNS per mostrare il record A o AAAA collegato a un nome host o indirizzo IP.
> Maggiori informazioni: <https://manned.org/ahost>.

- Stampa un record `A` o `AAAA` associato a un nome host o indirizzo IP:

`ahost {{example.com}}`

- Mostra output di debug aggiuntivo:

`ahost -d {{example.com}}`

- Mostra il record con un tipo specificato:

`ahost -t {{a|aaaa|u}} {{example.com}}`
