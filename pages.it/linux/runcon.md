# runcon

> Esegue un programma in un contesto di sicurezza SELinux diverso.
> Vedi anche: `secon`.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/runcon-invocation.html>.

- Stampa il contesto di sicurezza del contesto di esecuzione corrente:

`runcon`

- Specifica il dominio in cui eseguire un comando:

`runcon {{[-t|--type]}} {{domain}}_t {{command}}`

- Specifica il ruolo del contesto con cui eseguire un comando:

`runcon {{[-r|--role]}} {{role}}_r {{command}}`

- Specifica il contesto completo con cui eseguire un comando:

`runcon {{user}}_u:{{role}}_r:{{domain}}_t {{command}}`
