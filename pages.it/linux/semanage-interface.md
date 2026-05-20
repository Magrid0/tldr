# semanage interface

> Gestisce le definizioni dei tipi di interfaccia di rete SELinux.
> Vedi anche: `semanage`, `semanage-port`.
> Maggiori informazioni: <https://manned.org/semanage-interface>.

- Elenca tutte le definizioni dei tipi di interfaccia:

`sudo semanage interface {{[-l|--list]}}`

- Aggiunge una definizione di tipo di interfaccia di rete:

`sudo semanage interface {{[-a|--add]}} {{[-t|--type]}} {{nome_tipo}} {{nome_interfaccia}}`

- Elimina una definizione di tipo di interfaccia di rete:

`sudo semanage interface {{[-d|--delete]}} {{nome_interfaccia}}`

- Modifica una definizione di tipo di interfaccia di rete:

`sudo semanage interface {{[-m|--modify]}} {{[-t|--type]}} {{nome_tipo}} {{nome_interfaccia}}`

- Elenca le definizioni dei tipi di interfaccia in un formato personalizzato:

`sudo semanage interface {{[-l|--list]}} {{[-C|--locallist]}}`
