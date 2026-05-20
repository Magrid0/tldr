# cbatticon

> Un'icona della batteria leggera e veloce che risiede nella barra di sistema.
> Maggiori informazioni: <https://github.com/valr/cbatticon>.

- Mostra l'icona della batteria nella barra di sistema:

`cbatticon`

- Mostra l'icona della batteria e imposta l'intervallo di aggiornamento a 20 secondi:

`cbatticon {{[-u|--update-interval]}} {{20}}`

- Elenca i tipi di icona disponibili:

`cbatticon {{[-t|--list-icon-types]}}`

- Mostra l'icona della batteria con un tipo di icona specifico:

`cbatticon {{[-i|--icon-type]}} {{standard|notification|symbolic}}`

- Elenca gli alimentatori disponibili:

`cbatticon {{[-p|--list-power-supplies]}}`

- Mostra l'icona della batteria per una batteria specifica:

`cbatticon {{BAT0}}`

- Mostra l'icona della batteria e il comando da eseguire quando il livello della batteria raggiunge il livello critico impostato:

`cbatticon {{[-r|--critical-level]}} {{5}} {{[-c|--command-critical-level]}} {{poweroff}}`
