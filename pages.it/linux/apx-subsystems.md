# apx subsystems

> Gestisce i sottosistemi in `apx`.
> I sottosistemi sono container che possono essere creati basandosi su stack preesistenti.
> Maggiori informazioni: <https://docs.vanillaos.org/docs/en/apx-manpage#subsystems>.

- Crea interattivamente un nuovo sottosistema:

`apx subsystems new`

- Elenca tutti i sottosistemi disponibili:

`apx subsystems list`

- Reimposta un sottosistema specifico al suo stato iniziale:

`apx subsystems reset {{[-n|--name]}} {{stringa}}`

- Forza il ripristino di un sottosistema specifico:

`apx subsystems reset {{[-n|--name]}} {{stringa}} {{[-f|--force]}}`

- Rimuove un sottosistema specifico:

`apx subsystems rm {{[-n|--name]}} {{stringa}}`

- Forza la rimozione di un sottosistema specifico:

`apx subsystems rm {{[-n|--name]}} {{stringa}} {{[-f|--force]}}`
