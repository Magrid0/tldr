# dnsrecon

> Strumento di enumerazione DNS.
> Maggiori informazioni: <https://manned.org/dnsrecon>.

- Analizza un dominio e salva i risultati in un database SQLite:

`dnsrecon {{[-d|--domain]}} {{example.com}} --db {{path/to/database.sqlite}}`

- Analizza un dominio, specificando il nameserver ed eseguendo un transfer di zona:

`dnsrecon {{[-d|--domain]}} {{example.com}} {{[-n|--name_server]}} {{nameserver.example.com}} {{[-t|--type]}} axfr`

- Analizza un dominio, usando un attacco di brute-force e un dizionario di sottodomini e hostname:

`dnsrecon {{[-d|--domain]}} {{example.com}} {{[-D|--dictionary]}} {{path/to/dictionary.txt}} {{[-t|--type]}} brt`

- Analizza un dominio, eseguendo un reverse lookup degli intervalli IP dal record SPF e salvando i risultati in un file JSON:

`dnsrecon {{[-d|--domain]}} {{example.com}} -s {{[-j|--json]}}`

- Analizza un dominio, eseguendo un'enumerazione Google e salvando i risultati in un file CSV:

`dnsrecon {{[-d|--domain]}} {{example.com}} -g {{[-c|--csv]}}`

- Analizza un dominio, eseguendo DNS cache snooping:

`dnsrecon {{[-d|--domain]}} {{example.com}} {{[-t|--type]}} snoop {{[-n|--name_server]}} {{nameserver.example.com}} {{[-D|--dictionary]}} {{path/to/dictionary.txt}}`

- Analizza un dominio, eseguendo zone walking:

`dnsrecon {{[-d|--domain]}} {{example.com}} {{[-t|--type]}} zonewalk`
