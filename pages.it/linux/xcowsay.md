# xcowsay

> Mostra una mucca carina e un messaggio sul desktop Linux.
> La mucca viene mostrata per un periodo di tempo fisso o calcolato in base alla dimensione del testo. Fai clic sulla mucca per rimuoverla immediatamente.
> Maggiori informazioni: <https://manned.org/xcowsay>.

- Mostra una mucca che dice "hello, world":

`xcowsay "{{hello, world}}"`

- Mostra una mucca con l'output di un altro comando:

`ls | xcowsay`

- Mostra una mucca alle coordinate X e Y specificate:

`xcowsay --at {{X}},{{Y}}`

- Mostra una mucca di dimensioni diverse:

`xcowsay --cow-size {{small|med|large}}`

- Mostra un fumetto di pensiero invece di un fumetto di discorso:

`xcowsay --think`

- Mostra un'immagine diversa al posto della mucca predefinita:

`xcowsay --image {{path/to/file}}`
