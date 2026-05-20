# namei

> Segue un percorso (che può essere un collegamento simbolico) fino a trovare un punto terminale (file/directory/dispositivo carattere ecc.).
> Questo programma è utile per trovare problemi di "troppi livelli di collegamenti simbolici".
> Maggiori informazioni: <https://manned.org/namei>.

- Risolve i percorsi specificati come parametri:

`namei {{percorso/del/a}} {{percorso/del/b}} {{percorso/del/c}}`

- Mostra i risultati in un formato a elenco lungo:

`namei {{[-l|--long]}} {{percorso/del/a}} {{percorso/del/b}} {{percorso/del/c}}`

- Mostra i bit di modo di ogni tipo di file nello stile di `ls`:

`namei {{[-m|--modes]}} {{percorso/del/a}} {{percorso/del/b}} {{percorso/del/c}}`

- Mostra il proprietario e il gruppo di ogni file:

`namei {{[-o|--owners]}} {{percorso/del/a}} {{percorso/del/b}} {{percorso/del/c}}`

- Non segue i collegamenti simbolici durante la risoluzione:

`namei {{[-n|--nosymlinks]}} {{percorso/del/a}} {{percorso/del/b}} {{percorso/del/c}}`
