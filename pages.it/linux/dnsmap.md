# dnsmap

> Il comando dnsmap analizza un dominio alla ricerca di sottodomini comuni, ad esempio smtp.domain.org.
> Maggiori informazioni: <https://github.com/resurrecting-open-source-projects/dnsmap>.

- Analizza alla ricerca di sottodomini usando la wordlist interna:

`dnsmap {{example.com}}`

- Specifica un elenco di sottodomini da cercare:

`dnsmap {{example.com}} -w {{path/to/wordlist.txt}}`

- Salva i risultati in un file CSV:

`dnsmap {{example.com}} -c {{path/to/file.csv}}`

- Ignora 2 IP che sono falsi positivi (fino a 5 possibili):

`dnsmap {{example.com}} -i {{123.45.67.89,98.76.54.32}}`
