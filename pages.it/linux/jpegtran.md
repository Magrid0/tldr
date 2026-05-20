# jpegtran

> Esegue trasformazioni senza perdita di qualità di file JPEG.
> Maggiori informazioni: <https://manned.org/jpegtran>.

- Ribalta un'immagine orizzontalmente o verticalmente:

`jpegtran {{[-f|-flip]}} {{horizontal|vertical}} {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Ruota un'immagine di 90, 180 o 270 gradi in senso orario:

`jpegtran {{[-ro|-rotate]}} {{90|180|270}} {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Traspone l'immagine lungo l'asse dall'alto a sinistra in basso a destra:

`jpegtran -transpose {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Traspone l'immagine lungo l'asse dall'alto a destra in basso a sinistra:

`jpegtran -transverse {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Converte l'immagine in scala di grigi:

`jpegtran {{[-g|-grayscale]}} {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Ritaglia l'immagine in una regione rettangolare di larghezza `W` e altezza `H` dall'angolo in alto a sinistra, salvando l'output in un file specifico:

`jpegtran -crop {{W}}x{{H}} -outfile {{path/to/output.jpg}} {{path/to/image.jpg}}`

- Ritaglia l'immagine in una regione rettangolare di larghezza `W` e altezza `H`, a partire dal punto `X` e `Y` dall'angolo in alto a sinistra:

`jpegtran -crop {{W}}x{{H}}+{{X}}+{{Y}} {{path/to/image.jpg}} > {{path/to/output.jpg}}`
