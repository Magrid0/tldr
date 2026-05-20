# coredumpctl

> Recupera ed elabora i core dump salvati e i relativi metadati.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/coredumpctl.html>.

- Elenca tutti i core dump catturati:

`coredumpctl`

- Elenca i core dump catturati per un programma:

`coredumpctl list {{program}}`

- Mostra informazioni sui core dump corrispondenti a un programma con PID:

`coredumpctl info {{PID}}`

- Avvia il debugger utilizzando l'ultimo core dump:

`coredumpctl debug`

- Avvia il debugger utilizzando l'ultimo core dump di un programma:

`coredumpctl debug {{program}}`

- Estrae l'ultimo core dump di un programma in un file:

`coredumpctl {{[-o|--output]}} {{path/to/file}} dump {{program}}`

- Salta i prompt di debuginfod e paginazione e stampa il backtrace quando si utilizza `gdb`:

`coredumpctl debug {{[-A|--debugger-arguments]}} "-iex 'set debuginfod enabled on' -iex 'set pagination off' -ex bt"`
