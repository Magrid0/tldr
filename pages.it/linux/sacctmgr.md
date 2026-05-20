# sacctmgr

> Visualizza, configura e gestisci account Slurm.
> Maggiori informazioni: <https://slurm.schedmd.com/sacctmgr.html>.

- Mostra la configurazione corrente:

`sacctmgr show configuration`

- Aggiunge un cluster al database Slurm:

`sacctmgr add cluster {{nome_cluster}}`

- Aggiunge un account al database Slurm:

`sacctmgr add account {{nome_account}} cluster={{cluster_dell_account}}`

- Mostra i dettagli di utente/associazione/cluster/account usando un formato specifico:

`sacctmgr show {{user|association|cluster|account}} format="Account%10" format="GrpTRES%30"`
