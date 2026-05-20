# conntrack

> Interagisce con il sistema di tracciamento delle connessioni Netfilter.
> Cerca, elenca, ispeziona, modifica ed elimina i flussi di connessione.
> Maggiori informazioni: <https://manned.org/conntrack>.

- Elenca tutte le connessioni attualmente tracciate:

`conntrack {{[-L|--dump]}}`

- Mostra un registro eventi in tempo reale delle modifiche alle connessioni:

`conntrack {{[-E|--event]}}`

- Mostra un registro eventi in tempo reale delle modifiche alle connessioni con timestamp associati:

`conntrack {{[-E|--event]}} {{[-o|--output]}} timestamp`

- Mostra un registro eventi in tempo reale delle modifiche alle connessioni per un indirizzo IP specifico:

`conntrack {{[-E|--event]}} {{[-s|--orig-src]}} {{ip_address}}`

- Elimina tutti i flussi per un indirizzo IP di origine specifico:

`conntrack {{[-D|--delete]}} {{[-s|--orig-src]}} {{ip_address}}`
