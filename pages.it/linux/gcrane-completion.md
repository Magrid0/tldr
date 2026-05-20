# gcrane completion

> Genera lo script di autocompletamento per gcrane per la shell specificata.
> Le shell disponibili sono Bash, fish, PowerShell e Zsh.
> Maggiori informazioni: <https://github.com/google/go-containerregistry/blob/main/cmd/gcrane/README.md>.

- Genera lo script di autocompletamento per la tua shell:

`gcrane completion {{shell_name}}`

- Disabilita le descrizioni di completamento:

`gcrane completion {{shell_name}} --no-descriptions`

- Carica i completamenti nella sessione corrente della shell (Bash/Zsh):

`source <(gcrane completion bash/zsh)`

- Carica i completamenti nella sessione corrente della shell (fish):

`gcrane completion fish | source`

- Carica i completamenti per ogni nuova sessione (Bash):

`gcrane completion bash > /etc/bash_completion.d/gcrane`

- Carica i completamenti per ogni nuova sessione (Zsh):

`gcrane completion zsh > "${fpath[1]}/_gcrane"`

- Carica i completamenti per ogni nuova sessione (fish):

`gcrane completion fish > ~/.config/fish/completions/gcrane.fish`

- Mostra aiuto:

`gcrane completion {{shell_name}} {{[-h|--help]}}`
