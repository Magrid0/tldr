# getconf

> Ottiene valori di configurazione dal sistema Linux.
> Maggiori informazioni: <https://manned.org/getconf.1>.

- Elenca [t]utti i valori di configurazione disponibili:

`getconf -a`

- Elenca i valori di configurazione per una directory specifica:

`getconf -a {{path/to/directory}}`

- Verifica se il sistema è a 32 o 64 bit:

`getconf LONG_BIT`

- Verifica quanti processi l'utente corrente può eseguire contemporaneamente:

`getconf CHILD_MAX`

- Elenca ogni valore di configurazione e poi trova pattern con il comando `grep` (es. ogni valore con MAX):

`getconf -a | grep MAX`
