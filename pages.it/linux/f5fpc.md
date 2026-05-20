# f5fpc

> Un client VPN SSL proprietario commerciale di BIG-IP Edge.
> Maggiori informazioni: <https://my.f5.com/manage/s/article/K47922841>.

- Avvia una nuova connessione VPN:

`sudo f5fpc --start`

- Avvia una nuova connessione VPN verso un host specifico:

`sudo f5fpc --start --host {{host.example.com}}`

- Specifica un nome utente (verrà chiesta la password):

`sudo f5fpc --start --host {{host.example.com}} --username {{user}}`

- Mostra lo stato corrente della VPN:

`sudo f5fpc --info`

- Termina la connessione VPN:

`sudo f5fpc --stop`
