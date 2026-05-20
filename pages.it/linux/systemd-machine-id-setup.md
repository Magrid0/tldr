# systemd-machine-id-setup

> Inizializza l'ID macchina memorizzato in `/etc/machine-id` al momento dell'installazione con un ID fornito o generato casualmente.
> Nota: utilizzare sempre `sudo` per eseguire questi comandi poiché richiedono privilegi elevati.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-machine-id-setup.html>.

- Stampa l'ID macchina generato o impegnato:

`systemd-machine-id-setup --print`

- Specifica una policy per le immagini:

`systemd-machine-id-setup --image-policy {{tua_policy}}`

- Mostra l'output come JSON:

`sudo systemd-machine-id-setup --json pretty`

- Opera su un'immagine disco invece che su un albero di directory:

`systemd-machine-id-setup --image /{{percorso/dell/immagine}}`
