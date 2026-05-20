# imv

> Visualizzatore di immagini CLI per Wayland e X11 mirato ai window manager a piastrelle.
> Gestisce molteplici formati tra cui Photoshop (PSD).
> Maggiori informazioni: <https://sr.ht/~exec64/imv/>.

- Visualizza più immagini:

`imv {{path/to/image1.ext path/to/image2.ext ...}}`

- Visualizza in modalità schermo intero:

`imv -f {{path/to/image.ext}}`

- Visualizza le immagini ricorsivamente da un percorso:

`imv -r --slideshow {{path/to/directory}}`

- Apre più immagini tramite `stdin`:

`find . -type f -name "{{*.svg}}" | imv`

- Crea una presentazione da una directory mostrando ogni immagine per 10 secondi:

`imv -t 10 {{path/to/directory}}`

- Visualizza più immagini dal web:

`curl {{[-Osw|--remote-name --silent --write-out]}} '%{filename_effective}\n' '{{http://www.example.com/[1-10].jpg}}' | imv`
