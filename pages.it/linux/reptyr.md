# reptyr

> Sposta un processo in esecuzione in un nuovo terminale.
> Ideale quando ci si dimentica di avviare un'attività a lunga esecuzione in `screen`.
> Maggiori informazioni: <https://github.com/nelhage/reptyr#usage>.

- Sposta un processo in esecuzione nel terminale corrente:

`reptyr {{pid}}`

- Si attacca a un processo usando il suo nome:

`reptyr $(pidof {{htop}})`
