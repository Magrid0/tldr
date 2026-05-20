# imgp

> Ridimensiona e ruota immagini JPEG e PNG.
> Maggiori informazioni: <https://github.com/jarun/imgp#usage>.

- Converte singole immagini e/o intere directory contenenti formati immagine validi:

`imgp {{[-x|--res]}} {{1366x1000}} {{path/to/directory}} {{path/to/file}}`

- Ridimensiona un'immagine al 75% e sovrascrive l'immagine sorgente a una risoluzione target:

`imgp {{[-x|--res]}} {{75}} z-w {{path/to/file}}`

- Ruota un'immagine in senso orario di 90 gradi:

`imgp {{[-o|--rotate]}} {{90}} {{path/to/file}}`
