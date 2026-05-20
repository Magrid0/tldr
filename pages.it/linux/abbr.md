# abbr

> Gestisce le abbreviazioni per la shell fish.
> Parole definite dall'utente vengono sostituite con frasi più lunghe dopo essere state inserite.
> Maggiori informazioni: <https://fishshell.com/docs/current/cmds/abbr.html>.

- Aggiunge una nuova abbreviazione:

`abbr {{[-a|--add]}} {{nome_abbreviazione}} {{comando}} {{argomenti_comando}}`

- Rinomina un'abbreviazione esistente:

`abbr --rename {{vecchio_nome}} {{nuovo_nome}}`

- Cancella un'abbreviazione esistente:

`abbr {{[-e|--erase]}} {{nome_abbreviazione}}`

- Importa le abbreviazioni definite su un altro host tramite SSH:

`ssh {{nome_host}} abbr {{[-s|--show]}} | source`
