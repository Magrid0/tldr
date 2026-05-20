# xdg-mime

> Interroga e gestisce i tipi MIME secondo lo standard XDG.
> Maggiori informazioni: <https://portland.freedesktop.org/doc/xdg-mime.html>.

- Mostra il tipo MIME di un file:

`xdg-mime query filetype {{path/to/file}}`

- Mostra l'applicazione predefinita per aprire PNG:

`xdg-mime query default {{image/png}}`

- Mostra l'applicazione predefinita per aprire un file specifico:

`xdg-mime query default $(xdg-mime query filetype {{path/to/file}})`

- Imposta imv come applicazione predefinita per aprire immagini PNG e JPEG:

`xdg-mime default {{imv.desktop}} {{image/png}} {{image/jpeg}}`
