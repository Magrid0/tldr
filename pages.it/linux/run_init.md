# run_init

> Esegue script init nel contesto SELinux appropriato.
> Tipicamente usato per eseguire script di servizio di sistema con domini SELinux corretti.
> Vedi anche: `runcon`, `semanage`.
> Maggiori informazioni: <https://manned.org/run_init>.

- Esegue uno script nel contesto init:

`sudo run_init {{path/to/script}}`

- Esegue uno script con argomenti:

`sudo run_init {{path/to/script}} {{start|stop|restart}}`

- Esegue uno script e specifica esplicitamente il contesto dello script init:

`sudo run_init {{[-t|--type]}} {{context_type}} {{path/to/script}}`

- Mostra il contesto che verrebbe usato senza eseguire lo script:

`sudo run_init {{[-n|--dry-run]}} {{path/to/script}}`
