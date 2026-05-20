# abrt-action-analyze-backtrace

> Analizza il backtrace C/C++.
> Genera un hash di duplicazione, una valutazione del backtrace e identifica la funzione di crash.
> Salva i dati come nuovi elementi `duphash`, `rating`, `crash_function` nella directory del problema.
> Maggiori informazioni: <https://manned.org/abrt-action-analyze-backtrace>.

- Analizza il backtrace per la directory di lavoro corrente:

`abrt-action-analyze-backtrace`

- Analizza il backtrace per una directory specifica:

`abrt-action-analyze-backtrace -d {{path/to/directory}}`

- Analizza il backtrace in modo verboso:

`abrt-action-analyze-backtrace -v`
