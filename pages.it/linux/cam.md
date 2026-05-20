# cam

> Interfaccia frontend per `libcamera`.
> Vedi anche: `v4l2-ctl`.
> Maggiori informazioni: <https://libcamera.org/docs.html>.

- Elenca le telecamere disponibili:

`cam {{[-l|--list]}}`

- Elenca i controlli di una telecamera:

`cam {{[-c|--camera]}} {{camera_index}} --list-controls`

- Scrive fotogrammi in una cartella:

`cam {{[-c|--camera]}} {{camera_index}} {{[-C|--capture=]}}{{frames_to_capture}} {{[-F|--file]}}`

- Mostra il feed della telecamera in una finestra:

`cam {{[-c|--camera]}} {{camera_index}} {{[-C|--capture]}} {{[-S|--sdl]}}`
