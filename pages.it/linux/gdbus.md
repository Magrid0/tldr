# gdbus

> Interagisce con oggetti D-Bus.
> Parte di GLib.
> Maggiori informazioni: <https://manned.org/gdbus>.

- Elenca tutti i nomi sul bus di sessione:

`gdbus list-names --session`

- Elenca tutti i nomi sul bus di sistema:

`gdbus list-names --system`

- Introspetta un oggetto per vedere le sue interfacce e metodi:

`gdbus introspect --session --dest {{destination_bus_name}} --object-path /{{path/to/object}}`

- Chiama un metodo su un oggetto con argomenti:

`gdbus call --session --dest {{destination_bus_name}} --object-path /{{path/to/object}} --method {{interface.method_name}} {{argument1 argument2 ...}}`

- Emette un segnale da un oggetto con argomenti:

`gdbus emit --session --object-path /{{path/to/object}} --signal {{interface.signal_name}} {{argument1 argument2 ...}}`

- Monitora tutti i messaggi sul bus di sessione:

`gdbus monitor --session`
