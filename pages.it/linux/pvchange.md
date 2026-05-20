# pvchange

> Cambia gli attributi di uno o più volumi fisici.
> Maggiori informazioni: <https://manned.org/pvchange>.

- Consenti l'allocazione su un volume fisico:

`sudo pvchange {{[-x|--allocatable]}} y {{/dev/sdXN}}`

- Impedisci l'allocazione su un volume fisico:

`sudo pvchange {{[-x|--allocatable]}} n {{/dev/sdXN}}`

- Ignora le aree di metadati su un volume fisico:

`sudo pvchange --metadataignore y {{/dev/sdXN}}`

- Smetti di ignorare le aree di metadati su un volume fisico:

`sudo pvchange --metadataignore n {{/dev/sdXN}}`

- Aggiungi un tag a un volume fisico:

`sudo pvchange --addtag {{tag}} {{/dev/sdXN}}`

- Genera un nuovo UUID per un volume fisico (usare con cautela):

`sudo pvchange --uuid {{/dev/sdXN}}`

- Cambia tutti i volumi fisici visibili (combina con altre opzioni come allocatable):

`sudo pvchange {{[-a|--all]}} {{[-x|--allocatable]}} y`
