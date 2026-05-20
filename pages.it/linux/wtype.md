# wtype

> Simula l'input della tastiera su Wayland, simile a `xdotool type` per X11.
> Vedi anche: `ydotool`.
> Maggiori informazioni: <https://manned.org/wtype>.

- Simula la digitazione di testo:

`wtype "{{Hello World}}"`

- Digita un tasto specifico:

`wtype -k {{Left}}`

- Premi un modificatore:

`wtype -M {{shift|ctrl|...}}`

- Rilascia un modificatore:

`wtype -m {{ctrl}}`

- Attendi tra i tasti (in millisecondi):

`wtype -d {{500}} -- "{{testo}}"`

- Leggi il testo da `stdin`:

`echo "{{testo}}" | wtype -`
