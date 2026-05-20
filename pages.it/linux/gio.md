# gio

> Gestisce file locali e virtuali (GVfs).
> Parte di GLib utilizzato nei sistemi basati su GNOME.
> Maggiori informazioni: <https://manned.org/gio>.

- Apre un file con l'applicazione predefinita (es. PDF, immagine):

`gio open {{path/to/file}}`

- Elenca i file in una directory:

`gio list {{path/to/directory}}`

- Mostra informazioni su un file:

`gio info {{path/to/file}}`

- Copia un file:

`gio copy {{path/to/source}} {{path/to/destination}}`

- Invia un file nel cestino (reversibile):

`gio trash {{path/to/file}}`

- Svuota il cestino:

`gio trash --empty`

- Avvia un'applicazione da un file `.desktop`:

`gio launch {{path/to/file}}.desktop`

- Marca un file `.desktop` come attendibile, permettendone l'esecuzione:

`gio set {{path/to/file}}.desktop metadata::trusted true`
