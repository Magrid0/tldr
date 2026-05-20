# Natural Selection 2

> Avvia un server Natural Selection 2 senza interfaccia grafica.
> Maggiori informazioni: <https://naturalselection.fandom.com/wiki/Dedicated_Server>.

- Avvia un server con le impostazioni predefinite:

`{{percorso/del}}/server_linux`

- Assegna al server un nome personalizzato che appare nel browser dei server:

`{{percorso/del}}/server_linux -name '{{nome_server}}'`

- Specifica una porta di connessione per il server:

`{{percorso/del}}/server_linux -port {{27015}}`

- Specifica il numero massimo di giocatori:

`{{percorso/del}}/server_linux -limit {{2..24}}`

- Specifica la mappa iniziale su cui il server parte:

`{{percorso/del}}/server_linux -map {{ns2_summit}}`

- Limita l'accesso al server con una password:

`{{percorso/del}}/server_linux -password {{password}}`

- Avvia un server con interfaccia di amministrazione webui:

`{{percorso/del}}/server_linux -webadmin -webport {{8080}}`
