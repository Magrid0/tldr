# slurp

> Seleziona una regione in un compositor Wayland.
> Maggiori informazioni: <https://github.com/emersion/slurp/blob/master/slurp.1.scd>.

- Seleziona una regione e la stampa su `stdout`:

`slurp`

- Seleziona una regione e la stampa su `stdout`, mostrando le dimensioni della selezione:

`slurp -d`

- Seleziona un singolo punto invece di una regione:

`slurp -p`

- Seleziona un'uscita e stampa il suo nome:

`slurp -o -f '%o'`

- Seleziona una regione specifica e ne fa uno screenshot senza bordi, usando `grim`:

`grim -g "$(slurp -w 0)"`

- Seleziona una regione specifica e ne fa un video senza bordi, usando `wf-recorder`:

`wf-recorder {{[-g|--geometry]}} "$(slurp -w 0)"`
