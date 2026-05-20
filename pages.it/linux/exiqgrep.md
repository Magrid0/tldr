# exiqgrep

> Script Perl che offre possibilità di fare `grep` nell'output della coda di Exim.
> Maggiori informazioni: <https://www.exim.org/exim-html-current/doc/html/spec_html/ch-exim_utilities.html>.

- Confronta l'indirizzo del mittente usando una ricerca senza distinzione tra maiuscole e minuscole:

`exiqgrep -f '<{{email@example.com}}>'`

- Confronta l'indirizzo del mittente e mostra solo gli ID dei messaggi:

`exiqgrep -i -f '<{{email@example.com}}>'`

- Confronta l'indirizzo del [r]icevente:

`exiqgrep -r '{{email@example.com}}'`

- Rimuove tutti i messaggi che corrispondono all'indirizzo del mittente dalla coda:

`exiqgrep -i -f '<{{email@example.com}}>' | xargs exim -Mrm`

- Cerca messaggi rimbalzati:

`exiqgrep -f '^<>$'`

- Mostra il [c]onteggio dei messaggi rimbalzati:

`exiqgrep -c -f '^<>$'`
