# sealert

> Analizza e spiega i messaggi di negazione AVC di SELinux.
> Parte del pacchetto `setroubleshoot-server`.
> Vedi anche: `audit2why`, `ausearch`, `audit2allow`.
> Maggiori informazioni: <https://manned.org/sealert>.

- Analizza tutte le negazioni SELinux recenti:

`sudo sealert {{[-a|--analyze]}} {{/var/log/audit/audit.log}}`

- Analizza un ID alert specifico dai log di sistema:

`sudo sealert {{[-l|--lookupid]}} {{id_alert}}`

- Mostra un riepilogo degli alert SELinux recenti:

`sudo sealert {{[-b|--browser]}}`

- Monitora il log di audit in tempo reale per nuovi alert:

`sudo tail {{[-f|--follow]}} {{/var/log/audit/audit.log}} | sealert {{[-l|--lookupid]}} -`
