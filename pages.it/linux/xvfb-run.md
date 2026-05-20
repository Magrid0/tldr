# xvfb-run

> Esegue un comando in un ambiente server X virtuale.
> Maggiori informazioni: <https://manned.org/xvfb-run>.

- Esegui il comando specificato in un server X virtuale:

`xvfb-run {{comando}}`

- Prova a ottenere un numero di server libero, se quello predefinito (99) non è disponibile:

`xvfb-run {{[-a|--auto-servernum]}} {{comando}}`

- Passa argomenti al server Xvfb:

`xvfb-run {{[-s|--server-args]}} "{{-screen 0 1024x768x24}}" {{comando}}`
