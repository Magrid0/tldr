# arecord

> Registratore audio per il driver della scheda audio ALSA.
> Maggiori informazioni: <https://manned.org/arecord>.

- Registra un brano in qualità "CD" (termina con `<Ctrl c>` quando hai finito):

`arecord {{[-vv|--verbose --verbose]}} {{[-f|--format]}} cd {{path/to/file.wav}}`

- Registra un brano in qualità "CD", con una durata fissa di 10 secondi:

`arecord {{[-vv|--verbose --verbose]}} {{[-f|--format]}} cd {{[-d|--duration]}} {{10}} {{path/to/file.wav}}`

- Registra un brano e lo salva come MP3 (termina con `<Ctrl c>` quando hai finito):

`arecord {{[-vv|--verbose --verbose]}} {{[-f|--format]}} cd {{[-t|--file-type]}} raw | lame -r - {{path/to/file.mp3}}`

- Elenca tutte le schede audio e i dispositivi audio digitali:

`arecord {{[-l|--list-devices]}}`

- Consente l'interfaccia interattiva (es. usa `<Space>` o `<Enter>` per riprodurre o mettere in pausa):

`arecord {{[-i|--interactive]}}`

- Testa il microfono registrando un campione di 5 secondi e riproducendolo:

`arecord {{[-d|--duration]}} 5 test-mic.wav && aplay test-mic.wav && rm test-mic.wav`
