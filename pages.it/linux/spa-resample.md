# spa-resample

> Ricampiona un file audio usando il ricampionatore PipeWire.
> Nota: Questa utilità è principalmente destinata al test e al debug del ricampionatore.
> Maggiori informazioni: <https://docs.pipewire.org/page_man_spa-resample_1.html>.

- Ricampiona un file audio:

`spa-resample {{percorso/del/input.wav}} {{percorso/dell/output.wav}}`

- Ricampiona un file audio a una frequenza di campionamento specifica:

`spa-resample {{[-r|--rate]}} {{48000}} {{percorso/del/input.wav}} {{percorso/dell/output.wav}}`

- Ricampiona un file audio in un formato specifico:

`spa-resample {{[-f|--format]}} {{s8|s16|s32|f32|f64}} {{percorso/del/input.wav}} {{percorso/dell/output.wav}}`

- Ricampiona un file audio con una qualità specifica (0 è la più bassa, 14 è la più alta):

`spa-resample {{[-q|--quality]}} {{0..14}} {{percorso/del/input.wav}} {{percorso/dell/output.wav}}`

- Mostra aiuto:

`spa-resample -h`
