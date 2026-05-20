# shnsplit

> Divide file audio secondo un file `.cue`.
> Maggiori informazioni: <http://shnutils.freeshell.org/shntool/>.

- Divide un file `.wav` + `.cue` in più file:

`shnsplit -f {{percorso/del/file.cue}} {{percorso/del/file.wav}}`

- Mostra i formati supportati:

`shnsplit -a`

- Divide un file `.flac` in più file:

`shnsplit -f {{percorso/del/file.cue}} -o flac {{percorso/del/file.flac}}`

- Divide un file `.wav` in file con il formato "numero-traccia - album - titolo":

`shnsplit -f {{percorso/del/file.cue}} {{percorso/del/file.wav}} -t "%n - %a - %t"`
