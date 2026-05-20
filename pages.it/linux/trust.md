# trust

> Opera sull'archivio delle politiche di fiducia.
> Maggiori informazioni: <https://manned.org/trust>.

- Elenca gli elementi dell'archivio delle politiche di fiducia:

`trust list`

- Elenca informazioni su elementi specifici nell'archivio delle politiche di fiducia:

`trust list --filter={{blocklist|ca-anchors|certificates|trust-policy}}`

- Archivia un anchor di fiducia specifico nell'archivio delle politiche di fiducia:

`trust anchor {{percorso/del/certificato.crt}}`

- Rimuovi un anchor specifico dall'archivio delle politiche di fiducia:

`trust anchor --remove {{percorso/del/certificato.crt}}`

- Estrai la politica di fiducia dall'archivio condiviso:

`trust extract --format=x509-directory --filter=ca-anchors {{percorso/della/directory}}`

- Mostra l'aiuto per un sottocomando:

`trust {{sottocomando}} --help`
