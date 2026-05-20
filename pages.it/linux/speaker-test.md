# speaker-test

> Generatore di toni di test per altoparlanti per ALSA.
> Vedi anche: `aplay`, `arecord`, `amixer`.
> Maggiori informazioni: <https://manned.org/speaker-test>.

- Testa gli altoparlanti predefiniti con rumore rosa:

`speaker-test`

- Testa gli altoparlanti predefiniti con un file WAV predefinito:

`speaker-test {{[-t|--test]}} wav`

- Testa configurazioni di altoparlanti multicanale:

`speaker-test {{[-t|--test]}} wav {{[-c|--channels]}} {{1..8}}`

- Testa gli altoparlanti predefiniti con un file WAV specifico:

`speaker-test {{[-t|--test]}} wav {{[-w|--wavfile]}} {{percorso/del/file.wav}}`

- Testa gli altoparlanti predefiniti con un'onda sinusoidale:

`speaker-test {{[-t|--test]}} sine {{[-f|--frequency]}} {{frequenza}}`
