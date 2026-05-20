# pacrepairfile

> Reimposta le proprietà dei file gestiti da alpm.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/pacrepairfile.pod>.

- Cerca il pacchetto e reimposta le proprietà di un file:

`pacrepairfile {{percorso/del/file}} --package`

- Reimposta un file silenziosamente:

`pacrepairfile {{nome_pacchetto}} --quiet --package`

- Reimposta proprietà specifiche del file (modalità, UID proprietario, GID gruppo o data di modifica):

`pacrepairfile {{nome_pacchetto}} --{{mode|gid|mtime|uid}} --package`

- Mostra aiuto:

`pacrepairfile --help`

- Mostra versione:

`pacrepairfile --version`
