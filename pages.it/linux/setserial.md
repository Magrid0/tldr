# setserial

> Legge e modifica le informazioni delle porte seriali.
> Maggiori informazioni: <https://manned.org/setserial>.

- Stampa tutte le informazioni su un dispositivo seriale specifico:

`setserial -a {{/dev/cuaN}}`

- Stampa il riepilogo della configurazione di un dispositivo seriale specifico (utile per la stampa durante l'avvio):

`setserial -b {{dispositivo}}`

- Imposta un parametro di configurazione specifico su un dispositivo:

`sudo setserial {{dispositivo}} {{parametro}}`

- Stampa la configurazione di un elenco di dispositivi:

`setserial -g {{dispositivo1 dispositivo2 ...}}`
