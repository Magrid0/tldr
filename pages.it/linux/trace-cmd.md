# trace-cmd

> Utility per interagire con il tracer interno del kernel Linux Ftrace.
> Vedi anche: `trace-cmd list`, `trace-cmd record`, `trace-cmd report`.
> Maggiori informazioni: <https://manned.org/trace-cmd>.

- Mostra lo stato del sistema di tracing:

`sudo trace-cmd stat`

- Elenca i tracer disponibili:

`sudo trace-cmd list -t`

- Avvia il tracing con un plugin specifico:

`sudo trace-cmd start -p {{function|function_graph|preemptirqsoff|irqsoff|preemptoff|wakeup|...}}`

- Visualizza l'output del trace:

`sudo trace-cmd show`

- Ferma il tracing ma mantieni i buffer:

`sudo trace-cmd stop`

- Pulisci i buffer di trace:

`sudo trace-cmd clear`

- Registra un trace:

`sudo trace-cmd record`

- Mostra il trace registrato:

`sudo trace-cmd report`
