# apache2ctl

> Amministra il server web Apache HTTP.
> Questo comando è fornito con i sistemi basati su Debian, per quelli basati su RHEL vedi `httpd`.
> Maggiori informazioni: <https://manned.org/apache2ctl>.

- Avvia il demone Apache. Mostra un messaggio se è già in esecuzione:

`sudo apache2ctl start`

- Ferma il demone Apache:

`sudo apache2ctl stop`

- Riavvia il demone Apache:

`sudo apache2ctl restart`

- Testa la sintassi del file di configurazione:

`sudo apache2ctl -t`

- Elenca i moduli caricati:

`sudo apache2ctl -M`
