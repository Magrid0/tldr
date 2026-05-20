# curlie

> Un frontend per `curl` che aggiunge la facilità d'uso di `httpie`.
> Maggiori informazioni: <https://github.com/rs/curlie#usage>.

- Invia una richiesta GET:

`curlie {{httpbin.org/get}}`

- Invia una richiesta POST:

`curlie post {{httpbin.org/post}} {{name=john}} {{age:=25}}`

- Invia una richiesta GET con parametri di query (ad es. `first_param=5&second_param=true`):

`curlie get {{httpbin.org/get}} {{first_param==5}} {{second_param==true}}`

- Invia una richiesta GET con un'intestazione personalizzata:

`curlie get {{httpbin.org/get}} {{header-name:header-value}}`
