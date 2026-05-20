# asciiart

> Converte immagini in ASCII.
> Maggiori informazioni: <https://github.com/nodanaonlyzuul/asciiart#in-the-command-line>.

- Legge un'immagine da un file e la stampa in ASCII:

`asciiart {{path/to/immagine.jpg}}`

- Legge un'immagine da un URL e la stampa in ASCII:

`asciiart {{www.example.com/immagine.jpg}}`

- Sceglie la larghezza dell'output (predefinito è 100):

`asciiart {{[-w|--width]}} {{50}} {{path/to/immagine.jpg}}`

- Colora l'output ASCII:

`asciiart {{[-c|--color]}} {{path/to/immagine.jpg}}`

- Sceglie il formato dell'output (il formato predefinito è text):

`asciiart {{[-f|--format]}} {{text|html}} {{path/to/immagine.jpg}}`

- Inverte la mappa dei caratteri:

`asciiart {{[-i|--invert-chars]}} {{path/to/immagine.jpg}}`
