# rpcclient

> Strumento client MS-RPC (parte della suite samba).
> Maggiori informazioni: <https://www.samba.org/samba/docs/current/man-html/rpcclient.1.html>.

- Si connette a un host remoto:

`rpcclient {{[-U|--user]}} {{domain}}\{{username}}%{{password}} {{ip_address}}`

- Si connette a un host remoto su un dominio senza password:

`rpcclient {{[-U|--user]}} {{username}} {{[-W|--workgroup]}} {{domain}} {{[-N|--no-pass]}} {{ip_address}}`

- Si connette a un host remoto, passando l'hash della password:

`rpcclient {{[-U|--user]}} {{domain}}\{{username}} --pw-nt-hash {{ip_address}}`

- Esegue comandi shell su un host remoto:

`rpcclient {{[-U|--user]}} {{domain}}\{{username}}%{{password}} {{[-c|--command]}} {{semicolon_separated_commands}} {{ip_address}}`

- Mostra gli utenti del dominio:

`rpcclient $> enumdomusers`

- Mostra i privilegi:

`rpcclient $> enumprivs`

- Mostra informazioni su un utente specifico:

`rpcclient $> queryuser {{username|rid}}`

- Crea un nuovo utente nel dominio:

`rpcclient $> createdomuser {{username}}`
