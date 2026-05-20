# woeusb

> Strumento di creazione di supporti Windows.
> Maggiori informazioni: <https://manned.org/woeusb>.

- Formatta una USB e poi crea un'unità di installazione Windows avviabile:

`woeusb {{[-d|--device]}} {{percorso/di/windows.iso}} {{/dev/sdX}}`

- Copia i file Windows in una partizione esistente di un dispositivo USB di archiviazione e la rende avviabile, senza cancellare i dati correnti:

`woeusb {{[-p|--partition]}} {{percorso/di/windows.iso}} {{/dev/sdXN}}`
