# rc-service

> Trova ed esegue servizi OpenRC con argomenti.
> Vedi anche: `openrc`.
> Maggiori informazioni: <https://manned.org/rc-service>.

- Mostra lo stato di un servizio:

`rc-service {{service_name}} status`

- Avvia un servizio:

`sudo rc-service {{service_name}} start`

- Ferma un servizio:

`sudo rc-service {{service_name}} stop`

- Riavvia un servizio:

`sudo rc-service {{service_name}} restart`

- Simula l'esecuzione di un comando personalizzato di un servizio:

`sudo rc-service {{[-Z|--dry-run]}} {{service_name}} {{command_name}}`

- Esegue effettivamente un comando personalizzato di un servizio:

`sudo rc-service {{service_name}} {{command_name}}`

- Risolve la posizione di una definizione di servizio sul disco:

`sudo rc-service {{[-r|--resolve]}} {{service_name}}`
