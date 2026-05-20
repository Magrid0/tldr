# strigger

> Visualizza o modifica le informazioni sui trigger di Slurm.
> I trigger sono azioni che vengono eseguite automaticamente quando si verifica un evento su un cluster Slurm.
> Maggiori informazioni: <https://slurm.schedmd.com/strigger.html>.

- Registra un nuovo trigger. Esegue il programma specificato quando si verifica l'evento specificato:

`strigger --set --{{primary_database_failure|primary_slurmdbd_failure|primary_slurmctld_acct_buffer_full|primary_slurmctld_failure|...}} {{[-p|--program]}} {{percorso/dell/eseguibile}}`

- Esegue il programma specificato quando il job specificato termina:

`strigger --set {{[-j|--jobid]}} {{id_job}} {{[-f|--fini]}} {{[-p|--program]}} "{{percorso/dell/eseguibile}} {{argomento1 argomento2 ...}}"`

- Visualizza i trigger attivi:

`strigger --get`

- Visualizza i trigger attivi relativi al job specificato:

`strigger --get {{[-j|--jobid]}} {{id_job}}`

- Cancella il trigger specificato:

`strigger --clear {{id_trigger}}`
