# scrun

> Un proxy runtime OCI per Slurm che esegue container come job.
> Maggiori informazioni: <https://slurm.schedmd.com/scrun.html>.

- Crea un nuovo container con un ID specifico:

`scrun create {{id_container}}`

- Avvia un container creato in precedenza:

`scrun start {{id_container}}`

- Interroga lo stato di un container:

`scrun state {{id_container}}`

- Invia un segnale a un container (predefinito: SIGTERM):

`scrun kill {{id_container}}`

- Invia un segnale specifico a un container:

`scrun kill {{id_container}} {{SIGKILL}}`

- Elimina un container e rilascia le sue risorse:

`scrun delete {{id_container}}`

- Abilita il logging di debug:

`scrun {{create|start|kill|delete}} {{id_container}} --debug`

- Mostra versione:

`scrun --version`
