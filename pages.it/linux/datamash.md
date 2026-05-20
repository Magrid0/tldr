# datamash

> Esegue operazioni numeriche, testuali e statistiche di base su file di dati testuali.
> Maggiori informazioni: <https://www.gnu.org/software/datamash/manual/datamash.html#Invoking-datamash>.

- Ottiene max, min, media e mediana di una singola colonna di numeri:

`seq 3 | datamash max 1 min 1 mean 1 median 1`

- Ottiene la media di una singola colonna di numeri floating point (i float devono usare "," e non "."):

`echo -e '1.0\n2.5\n3.1\n4.3\n5.6\n5.7' | tr '.' ',' | datamash mean 1`

- Ottiene la media di una singola colonna di numeri con una data precisione decimale:

`echo -e '1\n2\n3\n4\n5\n5' | datamash {{[-R|--round]}} {{number_of_decimals_wanted}} mean 1`

- Ottiene la media di una singola colonna di numeri ignorando le stringhe "Na" e "NaN" (letterali):

`echo -e '1\n2\nNa\n3\nNaN' | datamash --narm mean 1`
