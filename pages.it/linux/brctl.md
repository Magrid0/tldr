# brctl

> Amministrazione bridge Ethernet.
> Maggiori informazioni: <https://manned.org/brctl>.

- Mostra un elenco con informazioni sui bridge Ethernet esistenti:

`sudo brctl show`

- Crea una nuova interfaccia bridge Ethernet:

`sudo brctl add {{bridge_name}}`

- Elimina un'interfaccia bridge Ethernet esistente:

`sudo brctl del {{bridge_name}}`

- Aggiunge un'interfaccia a un bridge esistente:

`sudo brctl addif {{bridge_name}} {{interface_name}}`

- Rimuove un'interfaccia da un bridge esistente:

`sudo brctl delif {{bridge_name}} {{interface_name}}`
