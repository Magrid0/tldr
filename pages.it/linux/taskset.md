# taskset

> Ottiene o imposta l'affinità della CPU di un processo o avvia un nuovo processo con un'affinità della CPU definita.
> Maggiori informazioni: <https://manned.org/taskset>.

- Ottiene l'affinità della CPU di un processo in esecuzione tramite PID:

`taskset {{[-p|--pid]}} {{[-c|--cpu-list]}} {{pid}}`

- Imposta l'affinità della CPU di un processo in esecuzione tramite PID:

`taskset {{[-p|--pid]}} {{[-c|--cpu-list]}} {{id_cpu}} {{pid}}`

- Avvia un nuovo processo con affinità per una singola CPU:

`taskset {{[-c|--cpu-list]}} {{id_cpu}} {{comando}}`

- Avvia un nuovo processo con affinità per più CPU non sequenziali:

`taskset {{[-c|--cpu-list]}} {{id_cpu_1,id_cpu_2,id_cpu_3,...}}`

- Avvia un nuovo processo con affinità per le CPU da 1 a 4:

`taskset {{[-c|--cpu-list]}} {{id_cpu_1}}-{{id_cpu_4}}`
