# wf-recorder

> Screencast per Wayland opzionalmente con audio.
> Per impostazione predefinita è necessario terminare il processo con `<Ctrl c>`.
> Maggiori informazioni: <https://github.com/ammen99/wf-recorder>.

- Registra salvando in un file MP4:

`wf-recorder {{[-f|--file]}} {{output.mp4}}`

- Registra includendo l'audio, sia da microfono che suoni di sistema:

`wf-recorder {{[-a|--audio]}} {{[-f|--file]}} /{{percorso/del/file_con_audio.webm}}`

- Seleziona e registra una porzione dello schermo usando `slurp`, con output in `recording.mp4` predefinito:

`wf-recorder {{[-g|--geometry]}} "$(slurp)"`
