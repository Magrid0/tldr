# pstree

> Un comodo strumento per mostrare i processi in esecuzione come albero.
> Maggiori informazioni: <https://manned.org/pstree>.

- Mostra un albero di tutti i processi (radicato in init):

`pstree`

- Mostra un albero dei processi con PID:

`pstree {{[-p|--show-pids]}}`

- Mostra tutti gli alberi dei processi radicati in processi posseduti dall'utente specificato:

`pstree {{utente}}`

- Mostra gli argomenti della riga di comando:

`pstree {{[-a|--arguments]}}`

- Mostra i figli di un processo specificato:

`pstree {{pid}}`

- Mostra i genitori di un processo specificato:

`pstree {{[-s|--show-parents]}} {{pid}}`
