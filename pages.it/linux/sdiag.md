# sdiag

> Mostra informazioni sull'esecuzione di `slurmctld`.
> Maggiori informazioni: <https://slurm.schedmd.com/sdiag.html>.

- Mostra tutti i contatori di prestazioni relativi all'esecuzione di `slurmctld`:

`sdiag {{[-a|--all]}}`

- Reimposta i contatori di prestazioni relativi all'esecuzione di `slurmctld`:

`sdiag {{[-r|--reset]}}`

- Specifica il formato di output:

`sdiag {{[-a|--all]}} --{{json|yaml}}`

- Specifica il cluster a cui inviare i comandi:

`sdiag {{[-a|--all]}} {{[-M|--cluster]}} {{nome_cluster}}`
