# pacgraph

> Disegna un grafico dei pacchetti installati in PNG/SVG/GUI/console.
> Maggiori informazioni: <https://manned.org/pacgraph>.

- Produce un grafico SVG e PNG:

`pacgraph`

- Produce un grafico SVG:

`pacgraph {{[-s|--svg]}}`

- Mostra un riepilogo nella console:

`pacgraph {{[-c|--console]}}`

- Sostituisci il nome/percorso predefinito (Nota: non specificare l'estensione del file):

`pacgraph {{[-f|--file]}} {{percorso/del/file}}`

- Cambia il colore dei pacchetti che non sono dipendenze:

`pacgraph {{[-t|--top]}} {{colore}}`

- Cambia il colore delle dipendenze dei pacchetti:

`pacgraph {{[-d|--dep]}} {{colore}}`

- Cambia il colore di sfondo del grafico:

`pacgraph {{[-b|--background]}} {{colore}}`

- Cambia il colore dei collegamenti tra pacchetti:

`pacgraph {{[-l|--link]}} {{colore}}`
