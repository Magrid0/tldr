# gcov

> Strumento di analisi e profilazione della copertura del codice che scopre parti non testate di un programma.
> Mostra anche una copia del codice sorgente annotata con le frequenze di esecuzione dei segmenti di codice.
> Maggiori informazioni: <https://gcc.gnu.org/onlinedocs/gcc/Invoking-Gcov.html>.

- Genera un report di copertura chiamato `file.cpp.gcov`:

`gcov {{path/to/file.cpp}}`

- Scrivi i conteggi di esecuzione individuali per ogni blocco di base:

`gcov {{[-a|--all-blocks]}} {{path/to/file.cpp}}`

- Scrivi le frequenze dei rami nel file di output e stampa le informazioni di riepilogo su `stdout` come percentuale:

`gcov {{[-b|--branch-probabilities]}} {{path/to/file.cpp}}`

- Scrivi le frequenze dei rami come numero di rami presi, invece della percentuale:

`gcov {{[-c|--branch-counts]}} {{path/to/file.cpp}}`

- Non creare un file di output `gcov`:

`gcov {{[-n|--no-output]}} {{path/to/file.cpp}}`

- Scrivi riepiloghi a livello di file e di funzione:

`gcov {{[-f|--function-summaries]}} {{path/to/file.cpp}}`
