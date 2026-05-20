# module

> Modifica l'ambiente di un utente.
> Maggiori informazioni: <https://lmod.readthedocs.io/en/latest/010_user.html>.

- Mostra i moduli disponibili:

`module avail`

- Cerca un modulo per nome:

`module avail {{module_name}}`

- Carica un modulo:

`module load {{module_name}}`

- Mostra i moduli caricati:

`module list`

- Scarica un modulo specifico caricato:

`module unload {{module_name}}`

- Scarica tutti i moduli caricati:

`module purge`

- Specifica moduli creati dall'utente:

`module use {{path/to/module_file1 path/to/module_file2 ...}}`

- Salva il set corrente di moduli caricati:

`module save {{collection_name}}`
