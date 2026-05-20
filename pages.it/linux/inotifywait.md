# inotifywait

> Attende modifiche ai file.
> Vedi anche: `fatrace`.
> Maggiori informazioni: <https://manned.org/inotifywait>.

- Osserva un file specifico per eventi, uscendo dopo il primo:

`inotifywait {{path/to/file}}`

- Osserva continuamente un file specifico per eventi senza uscire:

`inotifywait {{[-m|--monitor]}} {{path/to/file}}`

- Osserva ricorsivamente una directory per eventi:

`inotifywait {{[-m|--monitor]}} {{[-r|--recursive]}} {{path/to/directory}}`

- Osserva una directory per modifiche, escludendo file i cui nomi corrispondono a una `regex`:

`inotifywait {{[-m|--monitor]}} {{[-r|--recursive]}} --exclude "{{regex}}" {{path/to/directory}}`

- Osserva un file per modifiche, uscendo quando non si verifica alcun evento per 30 secondi:

`inotifywait {{[-m|--monitor]}} {{[-t|--timeout]}} {{30}} {{path/to/file}}`

- Osserva solo un file per eventi di modifica del file:

`inotifywait {{[-e|--event]}} {{modify}} {{path/to/file}}`

- Osserva un file stampando solo gli eventi e senza messaggi di stato:

`inotifywait {{[-q|--quiet]}} {{path/to/file}}`

- Esegue un comando quando un file viene acceduto:

`inotifywait {{[-e|--event]}} {{access}} {{path/to/file}} && {{command}}`
