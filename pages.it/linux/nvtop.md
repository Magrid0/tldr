# nvtop

> Visualizzatore interattivo basato su ncurses per processi GPU e stato per GPU AMD, Intel e NVIDIA.
> Vedi anche: `amdgpu_top`, `radeontop`.
> Maggiori informazioni: <https://manned.org/nvtop>.

- Avvia il monitor interattivo della GPU:

`nvtop`

- Imposta il ritardo di aggiornamento in decimi di secondo (ad esempio, 2 = 0,2 secondi):

`nvtop {{[-d|--delay]}} {{2}}`

- Esegue in modalità monocromatica (senza colore):

`nvtop {{[-C|--no-color]}}`

- Usa Fahrenheit per la visualizzazione della temperatura:

`nvtop {{[-f|--freedom-unit]}}`

- Mostra sempre i metri encoder/decoder, disabilitando la disattivazione automatica:

`nvtop {{[-E|--encode-hide]}} -1`

- Mostra un singolo grafico a barre combinato invece di grafici per GPU:

`nvtop {{[-p|--no-plot]}}`

- Mostra la versione del programma:

`nvtop {{[-v|--version]}}`
