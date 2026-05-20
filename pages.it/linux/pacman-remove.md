# pacman --remove

> Rimuove pacchetti dal sistema.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://manned.org/pacman.8>.

- [R]imuovi un pacchetto e le sue dipendenze ricor[s]ivamente:

`sudo pacman -Rs {{pacchetto}}`

- [R]imuovi un pacchetto e le sue dipendenze. Inoltre [n]on salvare backup dei file di configurazione:

`sudo pacman -Rsn {{pacchetto}}`

- [R]imuovi un pacchetto senza chiedere conferma:

`sudo pacman -R --noconfirm {{pacchetto}}`

- [R]imuovi i pacchetti orfani (installati come [d]ipendenze ma non più ritenu[t]i necessari da alcun pacchetto):

`sudo pacman -Rsn $(pacman -Qdtq)`

- [R]imuovi un pacchetto e [c]atena a tutti i pacchetti che dipendono da esso:

`sudo pacman -Rc {{pacchetto}}`

- Elenca e [p]rinta i pacchetti che sarebbero interessati (non [R]imuove alcun pacchetto):

`pacman -Rp {{pacchetto}}`

- Mostra [h]elp:

`pacman -Rh`
