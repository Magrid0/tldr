# sm

> Mostra un breve messaggio a schermo intero.
> Maggiori informazioni: <https://github.com/nomeata/screen-message>.

- Mostra un messaggio a schermo intero:

`sm "{{Hello World!}}"`

- Mostra un messaggio con colori invertiti:

`sm {{[-i|--invert]}} "{{Hello World!}}"`

- Mostra un messaggio con un colore di primo piano personalizzato:

`sm {{[-f|--foreground]}} {{blue}} "{{Hello World!}}"`

- Mostra un messaggio con un colore di sfondo personalizzato:

`sm {{[-b|--background]}} {{#008888}} "{{Hello World!}}"`

- Mostra un messaggio ruotato 3 volte (in passi di 90 gradi, in senso antiorario):

`sm {{[-r|--rotate]}} {{3}} "{{Hello World!}}"`

- Mostra un messaggio usando l'output di un altro comando:

`{{echo "Hello World!"}} | sm -`
