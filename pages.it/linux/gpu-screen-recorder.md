# gpu-screen-recorder

> Registra lo schermo e codifica il video con una GPU.
> Maggiori informazioni: <https://git.dec05eba.com/gpu-screen-recorder/about/>.

- Seleziona una sorgente usando un portale desktop e la registra:

`gpu-screen-recorder -w portal -o {{path/to/video.mp4}}`

- Specifica una sorgente video specifica:

`gpu-screen-recorder -w {{screen|DP-1|HDMI-A1|...}} -o {{path/to/video.mp4}}`

- Elenca le sorgenti di acquisizione video:

`gpu-screen-recorder --list-capture-options`

- Elenca le sorgenti di acquisizione audio:

`gpu-screen-recorder {{--list-audio-devices|--list-application-audio}}`

- Registra usando il buffer di replay:

`gpu-screen-recorder -w {{screen}} -r {{30}} -c {{mp4}} -ro {{path/to/directory}} -o {{whatever}}`

- Cattura un video dal buffer di replay:

`pkill -SIGUSR1 -f gpu-screen-recorder`

- Esegue `gpu-screen-recorder` in background:

`systemctl start --user gpu-screen-recorder`
