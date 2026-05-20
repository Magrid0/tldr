# service

> Gestisce i servizi eseguendo script init.
> Il percorso completo dello script deve essere omesso (viene assunto `/etc/init.d/`).
> Maggiori informazioni: <https://manned.org/service>.

- Elenca il nome e lo stato di tutti i servizi:

`service --status-all`

- Avvia/Ferma/Riavvia/Ricarica un servizio (avvio/arresto dovrebbero essere sempre disponibili):

`service {{nome_servizio}} {{start|stop|restart|reload}}`

- Esegue un riavvio completo (esegue lo script due volte con start e stop):

`service {{nome_servizio}} --full-restart`

- Mostra lo stato corrente di un servizio:

`service {{nome_servizio}} status`
