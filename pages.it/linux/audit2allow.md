# audit2allow

> Genera regole di autorizzazione della policy SELinux dai log di audit.
> Parte del pacchetto `policycoreutils-python-utils`.
> Vedi anche: `audit2why`, `ausearch`, `semodule`.
> Maggiori informazioni: <https://manned.org/audit2allow>.

- Genera regole di autorizzazione dai recenti rifiuti di audit e le mostra:

`sudo audit2allow {{[-a|--all]}}`

- Genera regole di autorizzazione da un file di log di audit specifico:

`sudo audit2allow {{[-i|--input]}} {{path/to/audit.log}}`

- Genera un modulo di policy dai recenti rifiuti di audit:

`sudo audit2allow {{[-a|--all]}} {{[-M|--module]}} {{nome_modulo}}`

- Spiega perché si sono verificati i rifiuti SELinux (uguale a `audit2why`):

`sudo audit2allow {{[-a|--all]}} --why`

- Mostra informazioni dettagliate sui messaggi generati:

`sudo audit2allow {{[-a|--all]}} {{[-e|--explain]}}`

- Utilizza macro installate per generare una policy di riferimento:

`sudo audit2allow {{[-a|--all]}} {{[-R|--reference]}}`

- Genera regole di autorizzazione per un servizio specifico:

`sudo ausearch {{[-m|--message]}} avc {{[-c|--comm]}} {{nome_servizio}} | audit2allow {{[-M|--module]}} {{nome_policy}}`

- Abilita la modalità di output verboso:

`sudo audit2allow {{[-a|--all]}} {{[-v|--verbose]}}`
