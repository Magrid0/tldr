# at

> Esegue comandi una volta in un momento successivo.
> I risultati verranno inviati alla mail dell'utente.
> Maggiori informazioni: <https://manned.org/at>.

- Avvia il demone `atd`:

`systemctl start atd`

- Crea comandi interattivamente e li esegue tra 5 minuti (premi `<Ctrl d>` quando hai finito):

`at now + 5 minutes`

- Crea comandi interattivamente e li esegue a un'ora specifica:

`at {{hh:mm}}`

- Esegue un comando da `stdin` alle 10:00 di oggi:

`echo "{{comando}}" | at 1000`

- Esegue comandi da un file specificato il prossimo martedì:

`at -f {{path/to/file}} 9:30 PM Tue`

- Elenca tutti i job in coda per l'utente corrente (uguale a `atq`):

`at -l`

- Visualizza un job specifico:

`at -c {{numero_job}}`
