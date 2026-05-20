# mbw

> Benchmark della larghezza di banda della memoria.
> Maggiori informazioni: <https://manned.org/mbw>.

- Esegue 3 test di larghezza di banda della memoria con dimensione 512 MB:

`mbw -n 3 512`

- Esegue 3 test di larghezza di banda della memoria con dimensione 512 MB, mostra solo le statistiche, non le medie:

`mbw -n 3 -q -a 512`

- Esegue il test memcpy 3 volte con dimensione 512 MB, mostra solo le statistiche:

`mbw -n 3 -q -t{{0}} 512`

- Esegue il test memcpy 10 volte con blocchi da 1024 byte allocati per 8192 MB di memoria:

`mbw -n 10 -q -t{{2}} -b 1024 8192`

- Esegue il test dumb con dimensione 2048 MB, mostra solo le statistiche, esegue all'infinito:

`mbw -n 0 -t{{1}} -q 2048`
