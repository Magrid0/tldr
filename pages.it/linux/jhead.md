# jhead

> Manipola timestamp e dati EXIF delle immagini.
> Maggiori informazioni: <https://www.sentex.net/~mwandel/jhead/usage.html>.

- Mostra tutti i dati EXIF:

`jhead {{path/to/image.jpg}}`

- Imposta la data e ora del file sulla data di creazione EXIF (la data di creazione del file verrà modificata):

`jhead -ft {{path/to/image.jpg}}`

- Imposta l'ora EXIF sulla data e ora del file (i dati EXIF verranno modificati):

`jhead -dsft {{path/to/image.jpg}}`

- Rinomina tutti i file JPEG in base alla data di creazione EXIF nel formato `YYYY_MM_DD-HH_MM_SS.jpg`:

`jhead -n%Y_%m_%d-%H_%M_%S *.jpg`

- Ruota senza perdita di qualità tutte le immagini JPEG di 90, 180 o 270 gradi in base al tag di orientamento EXIF:

`jhead -autorot *.jpg`

- Aggiorna tutti i timestamp EXIF (Formato: +- ore:minuti:secondi) (esempio: ci si è dimenticati di cambiare il fuso orario della fotocamera - rimuovendo 1 ora dai timestamp):

`jhead -ta-1:00:00 *.jpg`

- Rimuove tutti i dati EXIF (incluse le miniature):

`jhead -purejpg {{path/to/image.jpg}}`
