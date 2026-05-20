# cloud-init

> Gestisce l'inizializzazione delle istanze cloud.
> Maggiori informazioni: <https://cloudinit.readthedocs.io/en/latest/reference/cli.html>.

- Mostra lo stato dell'esecuzione più recente di cloud-init:

`cloud-init status`

- Attende il completamento di cloud-init e poi riporta lo stato:

`cloud-init status --wait`

- Elenca le chiavi di metadati di primo livello disponibili per la query:

`cloud-init query --list-keys`

- Interroga i metadati dell'istanza memorizzati nella cache per ottenere dati:

`cloud-init query {{dot_delimited_variable_path}}`

- Pulisce log e artefatti per consentire a cloud-init di essere eseguito di nuovo:

`cloud-init clean`
