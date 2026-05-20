# sed

> Editor di flusso GNU per filtrare e trasformare testo.
> Vedi anche: `awk`, `ed`.
> Maggiori informazioni: <https://www.gnu.org/software/sed/manual/sed.html>.

- [s]ostituisce tutte le occorrenze di "mela" con "mango" su tutte le righe, stampa su `stdout`:

`{{comando}} | sed 's/mela/mango/g'`

- Sostituisce "mela" con "mango" direttamente in un file (sovrascrive il file originale):

`sed {{[-i|--in-place]}} 's/mela/mango/g' {{percorso/del/file}}`

- Esegue più sostituzioni in un unico comando:

`{{comando}} | sed -e '{{s/mela/mango/g}}' -e '{{s/arancia/lime/g}}'`

- Usa un delimitatore personalizzato (utile quando il pattern contiene barre):

`{{comando}} | sed '{{s#////#____#g}}'`

- [c]ancella le righe da 1 a 5 di un file e crea un backup del file originale con estensione `.orig`:

`sed {{[-i|--in-place=]}}.orig '1,5d' {{percorso/del/file}}`

- [s]tampa solo la prima riga su `stdout`:

`{{comando}} | sed {{[-n|--quiet]}} '1p'`

- [i]nserisce una nuova riga all'inizio di un file, sovrascrivendo il file originale:

`sed {{[-i|--in-place]}} '1i\testo della nuova riga\' {{percorso/del/file}}`

- Cancella le righe vuote (con o senza spazi/tab) da un file, sovrascrivendo il file originale:

`sed {{[-i|--in-place]}} '/^[[:space:]]*$/d' {{percorso/del/file}}`
