# su

> Cambia shell a un altro utente.
> Maggiori informazioni: <https://manned.org/su>.

- Passa a superutente (richiede la password di root):

`su`

- Passa a un dato utente (richiede la password dell'utente):

`su {{nome_utente}}`

- Passa a un dato utente e simula una shell di login completa:

`su - {{nome_utente}}`

- Esegue un comando come un altro utente:

`su - {{nome_utente}} {{[-c|--command]}} "{{comando}}"`

- Passa a un dato utente e usa una shell specifica (ad esempio Zsh, fish, Bash):

`su {{[-s|--shell]}} /{{percorso/della/shell}} {{nome_utente}}`

- Mostra aiuto:

`su {{[-h|--help]}}`

- Mostra versione:

`su {{[-V|--version]}}`
