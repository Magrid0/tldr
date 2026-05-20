# needrestart

> Verifica quali demoni devono essere riavviati dopo aggiornamenti di librerie.
> Maggiori informazioni: <https://manned.org/needrestart>.

- Elenca i processi obsoleti:

`needrestart`

- Riavvia i servizi interattivamente:

`sudo needrestart`

- Elenca i processi obsoleti in modalità [v]erbosa o [q]uieta:

`needrestart -{{v|q}}`

- Verifica se il [k]ernel è obsoleto:

`needrestart -k`

- Verifica se il microcodice della CPU è obsoleto:

`needrestart -w`

- Elenca i processi obsoleti in modalità [b]atch:

`needrestart -b`

- Elenca i processi obsoleti usando un file di [c]onfigurazione specifico:

`needrestart -c {{percorso/del/config}}`

- Mostra aiuto:

`needrestart --help`
