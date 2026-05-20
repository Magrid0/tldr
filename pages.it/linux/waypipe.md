# waypipe

> Esegue da remoto applicazioni grafiche sotto un compositor Wayland.
> Maggiori informazioni: <https://manned.org/waypipe>.

- Esegue un programma grafico da remoto e lo mostra localmente:

`waypipe ssh {{utente}}@{{server}} {{programma}}`

- Apre un tunnel SSH per eseguire qualsiasi programma da remoto e mostrarlo localmente:

`waypipe ssh {{utente}}@{{server}}`

- Salta il test per il supporto Vulkan:

`waypipe --test-skip-vulkan ssh {{utente}}@{{server}} {{programma}}`

- Mostra aiuto:

`waypipe {{[-h|--help]}}`
