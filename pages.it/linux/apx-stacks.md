# apx stacks

> Gestisce gli stack in `apx`.
> Nota: le configurazioni degli stack create dall'utente sono memorizzate in `~/.local/share/apx/stacks`.
> Maggiori informazioni: <https://docs.vanillaos.org/docs/en/apx-manpage#stacks>.

- Crea interattivamente una nuova configurazione di stack:

`apx stacks new`

- Aggiorna interattivamente una configurazione di stack:

`apx stacks update {{nome}}`

- Elenca tutte le configurazioni di stack disponibili:

`apx stacks list`

- Rimuove una configurazione di stack specificata:

`apx stacks rm --name {{stringa}}`

- Importa una configurazione di stack:

`apx stacks import --input {{path/to/stack.yml}}`

- Esporta la configurazione di stack (Nota: il flag di output è opzionale, viene esportata nella directory di lavoro corrente per impostazione predefinita):

`apx stacks export --name {{stringa}} --output {{path/to/file_output}}`
