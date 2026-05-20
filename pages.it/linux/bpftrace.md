# bpftrace

> Linguaggio di tracciamento ad alto livello per eBPF Linux.
> Maggiori informazioni: <https://github.com/bpftrace/bpftrace/blob/master/man/adoc/bpftrace.adoc>.

- Elenca tutte le sonde disponibili:

`sudo bpftrace -l`

- Esegue un programma one-liner (es. conteggio chiamate di sistema per programma):

`sudo bpftrace -e '{{tracepoint:raw_syscalls:sys_enter { @[comm] = count(); }}}'`

- Esegue un programma da un file:

`sudo bpftrace {{path/to/file}}`

- Traccia un programma per PID:

`sudo bpftrace -e '{{tracepoint:raw_syscalls:sys_enter /pid == 123/ { @[comm] = count(); }}}'`

- Esegue una prova a secco e mostra l'output in formato eBPF:

`sudo bpftrace -d -e '{{one_line_program}}'`

- Mostra versione:

`bpftrace {{[-V|--version]}}`
