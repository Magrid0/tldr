# ddrescue

> Strumento di recupero dati che legge dati da dispositivi a blocchi danneggiati.
> Maggiori informazioni: <https://www.gnu.org/software/ddrescue/manual/ddrescue_manual.html#Invoking-ddrescue>.

- Cattura un'immagine di un dispositivo, creando un file di log:

`sudo ddrescue {{/dev/sdb}} {{path/to/image.dd}} {{path/to/log.txt}}`

- Clona il disco A sul disco B, creando un file di log:

`sudo ddrescue {{[-f|--force]}} {{[-n|--no-scrape]}} {{/dev/sdX}} {{/dev/sdY}} {{path/to/log.txt}}`
