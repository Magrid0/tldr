# http_load

> Un tool di benchmarking HTTP.
> Esegue più richieste HTTP in parallelo per testare la produttività di un server web.
> Maggiori informazioni: <https://www.acme.com/software/http_load/>.

- Emula 20 richieste basate su un dato file di elenco URL al secondo per 60 secondi:

`http_load -rate {{20}} -seconds {{60}} {{path/to/urls.txt}}`

- Emula 5 richieste concorrenti basate su un dato file di elenco URL per 60 secondi:

`http_load -parallel {{5}} -seconds {{60}} {{path/to/urls.txt}}`

- Emula 1000 richieste a 20 richieste al secondo, basate su un dato file di elenco URL:

`http_load -rate {{20}} -fetches {{1000}} {{path/to/urls.txt}}`

- Emula 1000 richieste con 5 richieste concorrenti alla volta, basate su un dato file di elenco URL:

`http_load -parallel {{5}} -fetches {{1000}} {{path/to/urls.txt}}`
