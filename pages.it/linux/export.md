# export

> Esporta le variabili di shell nei processi figli.
> Maggiori informazioni: <https://www.gnu.org/software/bash/manual/bash.html#index-export>.

- Imposta una variabile d'ambiente:

`export {{VARIABILE}}={{valore}}`

- Rimuove una variabile d'ambiente:

`export -n {{VARIABILE}}`

- Esporta una [f]unzione nei processi figli:

`export -f {{NOME_FUNZIONE}}`

- Aggiunge un percorso alla variabile d'ambiente `$PATH`:

`export PATH=$PATH:{{path/to/da_aggiungere}}`

- [p]rinta un elenco delle variabili esportate attive in formato comando shell:

`export -p`
