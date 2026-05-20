# flameshot

> Utility per screenshot con interfaccia grafica.
> Supporta modifiche di base alle immagini, come testo, forme, colori e imgur.
> Maggiori informazioni: <https://flameshot.org/docs/advanced/commandline-options/>.

- Crea uno screenshot a schermo intero:

`flameshot full`

- Crea uno screenshot interattivo:

`flameshot gui`

- Crea uno screenshot e lo salva in un percorso specifico:

`flameshot gui {{[-p|--path]}} {{path/to/directory}}`

- Crea uno screenshot interattivo in modalità semplificata:

`flameshot launcher`

- Crea uno screenshot da un monitor specifico:

`flameshot screen {{[-n|--number]}} {{2}}`

- Crea uno screenshot e lo stampa su `stdout`:

`flameshot gui {{[-r|--raw]}}`

- Crea uno screenshot e lo copia negli appunti:

`flameshot gui {{[-c|--clipboard]}}`

- Crea uno screenshot con un ritardo specifico in millisecondi:

`flameshot full {{[-d|--delay]}} {{5000}}`
