# snapper

> Strumento di gestione di snapshot di filesystem.
> Maggiori informazioni: <http://snapper.io/manpages/snapper.html>.

- Elenca le configurazioni degli snapshot:

`snapper list-configs`

- Crea una configurazione snapper:

`snapper {{[-c|--config]}} {{config}} create-config {{percorso/della/directory}}`

- Crea uno snapshot con una descrizione:

`snapper {{[-c|--config]}} {{config}} create {{[-d|--description]}} "{{descrizione_snapshot}}"`

- Elenca gli snapshot per una configurazione:

`snapper {{[-c|--config]}} {{config}} list`

- Elimina uno snapshot:

`snapper {{[-c|--config]}} {{config}} delete {{numero_snapshot}}`

- Elimina un intervallo di snapshot:

`snapper {{[-c|--config]}} {{config}} delete {{snapshot1}}-{{snapshot2}}`
