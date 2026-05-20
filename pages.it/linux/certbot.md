# certbot

> L'agente Let's Encrypt per ottenere e rinnovare automaticamente certificati TLS.
> Successore di `letsencrypt`.
> Maggiori informazioni: <https://eff-certbot.readthedocs.io/en/latest/using.html>.

- Ottiene un nuovo certificato tramite autorizzazione webroot, senza installarlo automaticamente:

`sudo certbot certonly --webroot {{[-w|--webroot-path]}} {{path/to/webroot}} {{[-d|--domain]}} {{subdomain.example.com}}`

- Ottiene un nuovo certificato tramite autorizzazione `nginx`, installando automaticamente il nuovo certificato:

`sudo certbot --nginx {{[-d|--domain]}} {{subdomain.example.com}}`

- Ottiene un nuovo certificato tramite autorizzazione apache, installando automaticamente il nuovo certificato:

`sudo certbot --apache {{[-d|--domain]}} {{subdomain.example.com}}`

- Rinnova tutti i certificati Let's Encrypt che scadono tra 30 giorni o meno (non dimenticare di riavviare i server che li utilizzano):

`sudo certbot renew`

- Simula l'ottenimento di un nuovo certificato, senza salvare alcun certificato sul disco:

`sudo certbot --webroot {{[-w|--webroot-path]}} {{path/to/webroot}} {{[-d|--domain]}} {{subdomain.example.com}} --dry-run`

- Ottiene un certificato di prova non attendibile:

`sudo certbot --webroot {{[-w|--webroot-path]}} {{path/to/webroot}} {{[-d|--domain]}} {{subdomain.example.com}} --test-cert`
