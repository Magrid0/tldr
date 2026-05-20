# steghide

> Strumento di steganografia per formati di file JPEG, BMP, WAV e AU.
> Maggiori informazioni: <https://manned.org/steghide>.

- Incorpora dati in un PNG, richiedendo una passphrase:

`steghide embed {{[-cf|--coverfile]}} {{percorso/dell/immagine.png}} {{[-ef|--embedfile]}} {{percorso/dei/dati.txt}}`

- Estrae dati da un file audio WAV:

`steghide extract {{[-sf|--stegofile]}} {{percorso/del/suono.wav}}`

- Mostra informazioni sul file, tentando di rilevare un file incorporato:

`steghide info {{percorso/del/file.jpg}}`

- Incorpora dati in un'immagine JPEG, usando la massima compressione:

`steghide embed {{[-cf|--coverfile]}} {{percorso/dell/immagine.jpg}} {{[-ef|--embedfile]}} {{percorso/dei/dati.txt}} {{[-z|--compress]}} {{9}}`

- Ottiene l'elenco degli algoritmi e delle modalità di crittografia supportati:

`steghide encinfo`

- Incorpora dati crittografati in un'immagine JPEG, ad esempio con Blowfish in modalità CBC:

`steghide embed {{[-cf|--coverfile]}} {{percorso/dell/immagine.jpg}} {{[-ef|--embedfile]}} {{percorso/dei/dati.txt}} {{[-e|--encryption]}} {{blowfish|...}} {{cbc|...}}`
