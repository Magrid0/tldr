# as

> Assemblatore portatile GNU.
> Principalmente inteso per assemblare l'output di `gcc` da utilizzare con `ld`.
> Maggiori informazioni: <https://manned.org/as>.

- Assembla un file, scrivendo l'output in `a.out`:

`as {{path/to/file.s}}`

- Assembla l'output in un file specificato:

`as {{path/to/file.s}} -o {{path/to/file_output.o}}`

- Genera output più velocemente saltando la preelaborazione di spazi bianchi e commenti. (Dovrebbe essere usato solo per compilatori fidati):

`as -f {{path/to/file.s}}`

- Include un percorso specifico nell'elenco delle directory da cercare per i file specificati nelle direttive `.include`:

`as -I {{path/to/directory}} {{path/to/file.s}}`
