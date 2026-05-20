# cage

> Avvia applicazioni in modalità chiosco.
> Vedi anche: `gamescope`.
> Maggiori informazioni: <https://github.com/cage-kiosk/cage/blob/master/cage.1.scd>.

- Avvia un'applicazione:

`cage {{application}}`

- Passa argomenti all'applicazione:

`cage -- {{application}} {{arguments}}`

- Nasconde le decorazioni della finestra (questo può impedire l'accesso al terminale):

`cage -d {{application}}`

- Permette di cambiare terminale con `<Ctrl Alt F2>`:

`cage -s {{application}}`

- Mostra aiuto:

`cage -h`
