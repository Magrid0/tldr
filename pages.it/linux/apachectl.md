# apachectl

> Controlla un server Apache HTTP.
> Maggiori informazioni: <https://manned.org/apachectl>.

- Avvia il server:

`sudo apachectl start`

- Riavvia il server:

`sudo apachectl restart`

- Ferma il server:

`sudo apachectl stop`

- Testa la validità del file di configurazione:

`apachectl configtest`

- Controlla lo stato del server (richiede il browser lynx):

`apachectl status`

- Ricarica la configurazione senza interrompere le connessioni:

`sudo apachectl graceful`

- Stampa la configurazione completa di Apache (non sempre supportato):

`apachectl -S`

- Mostra aiuto:

`apachectl -h`
