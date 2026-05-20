# systemd-run

> Esegue programmi in unità di ambito transitorie, unità di servizio o unità di servizio attivate da percorso, socket o timer.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-run.html>.

- Avvia un servizio transitorio:

`sudo systemd-run {{comando}} {{argomento1 argomento2 ...}}`

- Avvia un servizio transitorio sotto il gestore dei servizi dell'utente corrente (senza privilegi):

`systemd-run --user {{comando}} {{argomento1 argomento2 ...}}`

- Avvia un servizio transitorio con un nome unità e una descrizione personalizzati:

`sudo systemd-run {{[-u|--unit]}} {{nome}} --description {{stringa}} {{comando}} {{argomento1 argomento2 ...}}`

- Avvia un servizio transitorio che non viene pulito dopo la terminazione con una variabile d'ambiente personalizzata:

`sudo systemd-run {{[-r|--remain-after-exit]}} --set-env={{nome}}={{valore}} {{comando}} {{argomento1 argomento2 ...}}`

- Avvia un timer transitorio che esegue periodicamente il suo servizio transitorio (vedere `man systemd.time` per il formato degli eventi calendario):

`sudo systemd-run --on-calendar={{evento_calendario}} {{comando}} {{argomento1 argomento2 ...}}`

- Condivide il terminale con il programma (permettendo input/output interattivi) e assicura che i dettagli di esecuzione rimangano dopo l'uscita del programma:

`systemd-run {{[-r|--remain-after-exit]}} --pty {{comando}}`

- Imposta proprietà (es. CPUQuota, MemoryMax) del processo e attende che termini:

`systemd-run {{[-p|--property]}} MemoryMax={{byte_memoria}} {{[-p|--property]}} CPUQuota={{percentuale_tempo_cpu}}% --wait {{comando}}`

- Utilizza il programma in una pipeline di shell:

`{{comando1}} | systemd-run {{[-P|--pipe]}} {{comando2}} | {{comando3}}`
