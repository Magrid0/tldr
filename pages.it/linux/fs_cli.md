# fs_cli

> Connette e controlla un server FreeSWITCH in esecuzione utilizzando l'interfaccia a riga di comando di FreeSWITCH (client ESL).
> Maggiori informazioni: <https://developer.signalwire.com/freeswitch/FreeSWITCH-Explained/Client-and-Developer-Interfaces/1048948/>.

- Connette all'istanza FreeSWITCH locale con una sessione interattiva:

`fs_cli`

- Connette a un server FreeSWITCH remoto:

`fs_cli {{[-H|--host]}} {{host}} {{[-P|--port]}} {{port}} {{[-p|--password]}} {{password}}`

- Esegue un singolo comando FreeSWITCH ed esce:

`fs_cli {{[-x|--execute]}} "{{command}}"`

- Mostra lo stato del sistema FreeSWITCH:

`fs_cli {{[-x|--execute]}} "status"`

- Ricarica la configurazione XML di FreeSWITCH:

`fs_cli {{[-x|--execute]}} "reloadxml"`

- Controlla se un modulo è caricato:

`fs_cli {{[-x|--execute]}} "module_exists {{module_name}}"`

- Mostra le chiamate attive:

`fs_cli {{[-x|--execute]}} "show calls"`

- Riprova la connessione in caso di fallimento:

`fs_cli {{[-r|--retry]}}`
