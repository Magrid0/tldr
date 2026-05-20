# sic

> Client IRC semplice.
> Parte degli strumenti suckless.
> Maggiori informazioni: <https://manned.org/sic>.

- Si connette all'host predefinito (irc.ofct.net) con il nickname impostato nella variabile d'ambiente `$USER`:

`sic`

- Si connette a un host dato, usando un nickname dato:

`sic -h {{host}} -n {{nickname}}`

- Si connette a un host dato, usando un nickname e una password dati:

`sic -h {{host}} -n {{nickname}} -k {{password}}`

- Si unisce a un canale:

`:j #{{canale}}<Enter>`

- Invia un messaggio a un canale o utente:

`:m #{{canale|utente}}<Enter>`

- Imposta il canale o utente predefinito:

`:s #{{canale|utente}}<Enter>`
