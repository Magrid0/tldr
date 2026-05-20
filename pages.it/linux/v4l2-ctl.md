# v4l2-ctl

> Controlla i dispositivi video.
> Vedi anche: `cam`.
> Maggiori informazioni: <https://manned.org/v4l2-ctl>.

- Elenca tutti i dispositivi video:

`v4l2-ctl {{[-A|--list-devices]}}`

- Elenca i formati video e le risoluzioni supportati del dispositivo video predefinito `/dev/video0`:

`v4l2-ctl --list-formats-ext`

- Elenca i formati video e le risoluzioni supportati di un dispositivo video specifico:

`v4l2-ctl --list-formats-ext {{[-d|--device]}} {{percorso/del/dispositivo_video}}`

- Ottiene tutti i dettagli di un dispositivo video:

`v4l2-ctl --all {{[-d|--device]}} {{percorso/del/dispositivo_video}}`

- Cattura una foto JPEG con una risoluzione specifica dal dispositivo video:

`v4l2-ctl {{[-d|--device]}} {{percorso/del/dispositivo_video}} --set-fmt-video=width={{larghezza}},height={{altezza}},pixelformat=MJPG --stream-mmap --stream-to={{percorso/dell/output.jpg}} --stream-count=1`

- Cattura un flusso video raw dal dispositivo video:

`v4l2-ctl {{[-d|--device]}} {{percorso/del/dispositivo_video}} --set-fmt-video=width={{larghezza}},height={{altezza}},pixelformat={{formato}} --stream-mmap --stream-to={{percorso/dell/output}} --stream-count={{numero_di_fotogrammi_da_catturare}}`

- Elenca tutti i controlli del dispositivo video e i loro valori:

`v4l2-ctl {{[-l|--list-ctrls]}} {{[-d|--device]}} {{percorso/del/dispositivo_video}}`

- Imposta il valore di un controllo del dispositivo video:

`v4l2-ctl {{[-d|--device]}} {{percorso/del/dispositivo_video}} {{[-c|--set-ctrl]}} {{nome_controllo}}={{valore}}`
