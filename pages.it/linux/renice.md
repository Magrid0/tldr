# renice

> Modifica la priorità di scheduling/bontà dei processi in esecuzione.
> I valori di bontà vanno da -20 (più favorevole al processo) a 19 (meno favorevole al processo).
> Vedi anche: `nice`.
> Maggiori informazioni: <https://manned.org/renice>.

- Imposta la priorità assoluta di un processo in esecuzione:

`renice --priority {{3}} {{[-p|--pid]}} {{pid}}`

- Aumenta la priorità di un processo in esecuzione:

`sudo renice --relative {{-4}} {{[-p|--pid]}} {{pid}}`

- Diminuisce la priorità di tutti i processi posseduti da un utente:

`renice --relative {{4}} {{[-u|--user]}} {{uid|user}}`

- Imposta la priorità di tutti i processi che appartengono a un gruppo di processi:

`sudo renice {{-5}} {{[-g|--pgrp]}} {{process_group}}`
