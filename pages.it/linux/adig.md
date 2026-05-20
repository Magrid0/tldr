# adig

> Stampa le informazioni ricevute dai server DNS (Domain Name System).
> Maggiori informazioni: <https://manned.org/adig>.

- Mostra il record A (predefinito) dal DNS per uno o più nomi host:

`adig {{example.com}}`

- Mostra output di [d]ebug aggiuntivo:

`adig -d {{example.com}}`

- Si connette a un [s]erver DNS specifico:

`adig -s {{1.2.3.4}} {{example.com}}`

- Utilizza una porta TCP specifica per connettersi a un server DNS:

`adig -T {{porta}} {{example.com}}`

- Utilizza una porta UDP specifica per connettersi a un server DNS:

`adig -U {{porta}} {{example.com}}`
