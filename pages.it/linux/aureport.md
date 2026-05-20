# aureport

> Genera rapporti riepilogativi dei log di auditd.
> Maggiori informazioni: <https://manned.org/aureport>.

- Mostra un riepilogo degli eventi di auditd:

`sudo aureport`

- Genera un riepilogo degli eventi di login:

`sudo aureport {{[-l|--login]}}`

- Elenca tutti i rapporti sulle syscall:

`sudo aureport {{[-s|--syscall]}}`

- Genera un riepilogo degli eventi eseguibili:

`sudo aureport {{[-x|--executable]}}`

- Mostra un riepilogo degli eventi per un intervallo di tempo specifico:

`sudo aureport {{[-ts|--start]}} {{tempo_inizio}} {{[-te|--end]}} {{tempo_fine}}`

- Elenca tutti i file di audit e l'intervallo di tempo degli eventi che coprono:

`sudo aureport {{[-t|--log-time]}}`

- Mostra aiuto:

`aureport --help`
