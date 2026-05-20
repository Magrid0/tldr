# busctl

> Ispeziona e monitora il bus D-Bus.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/busctl.html>.

- Mostra tutti i peer sul bus tramite i loro nomi di servizio:

`busctl`

- Mostra informazioni sul processo e credenziali di un servizio bus, un processo o il proprietario del bus (se non viene specificato alcun parametro):

`busctl status {{service|pid}}`

- Scarica i messaggi scambiati. Se non viene specificato alcun servizio, mostra tutti i messaggi sul bus:

`busctl monitor {{service1 service2 ...}}`

- Mostra un albero degli oggetti di uno o più servizi (o di tutti i servizi se non viene specificato alcun servizio):

`busctl tree {{service1 service2 ...}}`

- Mostra interfacce, metodi, proprietà e segnali dell'oggetto specificato sul servizio specificato:

`busctl introspect {{service}} {{path/to/object}}`

- Recupera il valore corrente di una o più proprietà dell'oggetto:

`busctl get-property {{service}} {{path/to/object}} {{interface_name}} {{property_name}}`

- Invoca un metodo e mostra la risposta:

`busctl call {{service}} {{path/to/object}} {{interface_name}} {{method_name}}`
