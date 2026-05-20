# xwinwrap

> Esegue un lettore o un programma come sfondo del desktop.
> Maggiori informazioni: <https://github.com/r00tdaemon/xwinwrap>.

- Esegui un video usando mpv:

`xwinwrap -b -nf -ov -- {{mpv}} --wid {{wid}} --loop --no-audio --no-resume-playback --panscan={{1.0}} {{path/to/video.mp4}}`

- Esegui un video a schermo intero usando mpv:

`xwinwrap -b -nf -fs -ov -- {{mpv}} --wid {{wid}} --loop --no-audio --no-resume-playback --panscan={{1.0}} {{path/to/video.mp4}}`

- Esegui un video usando mpv con opacità all'80%:

`xwinwrap -b -nf -ov -o 0.8 --- {{mpv}} --wid {{wid}} --loop --no-audio --no-resume-playback --panscan={{1.0}} {{path/to/video.mp4}}`

- Esegui un video usando mpv in un secondo monitor 1600x900 con offset 1920 sull'asse X:

`xwinwrap -g 1600x900+1920 -b -nf -ov -- {{mpv}} --wid {{wid}} --loop --no-audio --no-resume-playback --panscan={{1.0}} {{path/to/video.mkv}}`
