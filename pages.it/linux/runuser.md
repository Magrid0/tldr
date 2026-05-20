# runuser

> Esegue comandi come un utente e gruppo senza chiedere la password.
> Maggiori informazioni: <https://manned.org/runuser>.

- Esegue un comando come un utente diverso:

`sudo runuser {{user}} {{[-c|--command]}} '{{command}}'`

- Esegue un comando come un utente e gruppo diverso:

`sudo runuser {{user}} {{[-g|--group]}} {{group}} {{[-c|--command]}} '{{command}}'`

- Avvia una shell di login come utente specifico:

`sudo runuser {{user}} {{[-l|--login]}}`

- Specifica una shell per l'esecuzione invece della shell predefinita (funziona anche per login):

`sudo runuser {{user}} {{[-s|--shell]}} {{/bin/sh}}`

- Mantiene l'intero ambiente di root (solo se `--login` non è specificato):

`sudo runuser {{user}} {{[-p|--preserve-environment]}} {{[-c|--command]}} '{{command}}'`
