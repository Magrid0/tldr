# ostree

> Controllo versione per file binari simile a `git` ma ottimizzato per filesystem root di sistemi operativi.
> OSTree è il fondamento per sistemi operativi immutabili basati su immagini come Fedora Silverblue, Fedora IoT o Fedora CoreOS.
> Maggiori informazioni: <https://ostreedev.github.io/ostree/>.

- Inizializza un repository dei file in `$PWD` con metadati in `$PWD/percorso/del/repo`:

`ostree init --repo {{percorso/del/repo}}`

- Crea un commit (istantanea) dei file:

`ostree commit --repo {{percorso/del/repo}} --branch {{nome_branch}}`

- Mostra i file nel commit:

`ostree ls --repo {{percorso/del/repo}} {{id_commit}}`

- Mostra i metadati del commit:

`ostree show --repo {{percorso/del/repo}} {{id_commit}}`

- Mostra l'elenco dei commit:

`ostree log --repo {{percorso/del/repo}} {{nome_branch}}`

- Mostra il riepilogo del repo:

`ostree summary --repo {{percorso/del/repo}} --view`

- Mostra i ref (branch) disponibili:

`ostree refs --repo {{percorso/del/repo}}`
