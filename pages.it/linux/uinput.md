# uinput

> Intercetta e scrivi eventi di input su un dispositivo di tastiera virtuale usando `/dev/uinput`.
> Maggiori informazioni: <https://gitlab.com/interception/linux/tools/-/tree/master#uinput>.

- Mostra il risultato dell'unione di descrizioni di dispositivo YAML ed esci (dry-run):

`uinput -p`

- Unisci descrizioni di dispositivo YAML in un dispositivo virtuale risultante:

`sudo uinput -c {{percorso/del/dispositivo1.yaml percorso/del/dispositivo2.yaml ...}}`

- Unisci la descrizione del dispositivo di riferimento dai nodi del dispositivo in un dispositivo virtuale risultante:

`sudo uinput -d {{/dev/input/eventX /dev/input/eventY ...}}`
