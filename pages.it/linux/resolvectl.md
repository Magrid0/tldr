# resolvectl

> Risolve nomi di dominio, indirizzi IPv4 e IPv6, record di risorse DNS e servizi.
> Nota: `systemd-resolved.service` deve essere in esecuzione.
> Vedi anche: `dig`, `nslookup`, `host`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/resolvectl.html>.

- Mostra le impostazioni DNS:

`resolvectl`

- Risolve gli indirizzi IPv4 e IPv6 per uno o più domini:

`resolvectl query {{domain1 domain2 ...}}`

- Recupera il dominio di un indirizzo IP specificato:

`resolvectl query {{ip_address}}`

- Cancella tutte le cache DNS locali:

`resolvectl flush-caches`

- Mostra le statistiche DNS (transazioni, cache e verdetti DNSSEC):

`resolvectl statistics`

- Recupera un record MX di un dominio:

`resolvectl --legend {{no}} {{[-t|--type]}} {{MX}} query {{domain}}`

- Risolve un record SRV, per esempio `_xmpp-server._tcp gmail.com`:

`resolvectl service _{{service}}._{{protocol}} {{name}}`

- Recupera una chiave TLS:

`resolvectl tlsa tcp {{domain}}:443`
