# systemd-cat

> Collega i flussi di output di una pipeline o di un programma con il journal di systemd.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-cat.html>.

- Scrive l'output del comando specificato nel journal (entrambi i flussi di output vengono catturati):

`systemd-cat {{comando}}`

- Scrive l'output di una pipeline nel journal (`stderr` rimane collegato al terminale):

`{{comando}} | systemd-cat`

- Utilizza l'identificatore specificato (predefinito: `cat` quando legge da una pipeline, nome dell'eseguibile altrimenti):

`{{comando}} | systemd-cat {{[-t|--identifier]}} {{id}}`

- Utilizza il livello di priorità predefinito specificato per tutti i messaggi registrati:

`systemd-cat {{[-p|--priority]}} {{emerg|alert|crit|err|warning|notice|info|debug}} {{comando}}`

- Utilizza il livello di priorità predefinito specificato per i messaggi registrati da `stderr` del comando:

`systemd-cat --stderr-priority {{emerg|alert|crit|err|warning|notice|info|debug}} {{comando}}`
