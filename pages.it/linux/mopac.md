# mopac

> MOPAC (Molecular Orbital PACkage) è un programma di chimica quantistica semiempirica basato sull'approssimazione NDDO di Dewar e Thiel.
> Maggiori informazioni: <https://github.com/openmopac/mopac>.

- Esegue calcoli secondo un file di input (`.mop`, `.dat` e `.arc`):

`mopac {{path/to/input_file}}`

- Esempio minimo funzionante con HF che scrive nella directory corrente e trasmette il file di output:

`touch test.out; echo "PM7\n#comment\n\nH 0.95506 0.05781 -0.03133\nF 1.89426 0.05781 -0.03133" > test.mop; mopac test.mop & tail {{[-f|--follow]}} test.out`
