# foreman

> Gestisce applicazioni basate su Procfile.
> Maggiori informazioni: <https://manned.org/foreman>.

- Avvia un'applicazione con il Procfile nella directory corrente:

`foreman start`

- Avvia un'applicazione con un Procfile specifico:

`foreman start {{[-f|--procfile]}} {{Procfile}}`

- Avvia un'applicazione specifica:

`foreman start {{process}}`

- Convalida il formato del Procfile:

`foreman check`

- Esegue comandi singoli con l'ambiente del processo:

`foreman run {{command}}`

- Avvia tutti i processi tranne quello denominato "worker":

`foreman start {{[-m|--formation]}} all=1,{{worker}}=0`
