# pacman-mirrors

> Genera una lista di mirror per `pacman` su Manjaro Linux.
> Ogni esecuzione di `pacman-mirrors` richiede di sincronizzare il database e aggiornare il sistema con `sudo pacman -Syyu`.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://wiki.manjaro.org/index.php?title=Pacman-mirrors>.

- Genera una lista di mirror usando le impostazioni predefinite:

`sudo pacman-mirrors --fasttrack`

- Ottieni lo stato dei mirror correnti:

`pacman-mirrors --status`

- Mostra il ramo corrente:

`pacman-mirrors --get-branch`

- Cambia a un ramo diverso:

`sudo pacman-mirrors --api --set-branch {{stable|unstable|testing}}`

- Genera una lista di mirror, usando solo mirror nel tuo paese:

`sudo pacman-mirrors --geoip`
