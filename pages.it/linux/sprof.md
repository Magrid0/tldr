# sprof

> Legge e mostra i dati di profilazione degli oggetti condivisi.
> Nota: richiede dati di profilazione generati tramite la variabile d'ambiente `$LD_PROFILE`.
> Maggiori informazioni: <https://manned.org/sprof>.

- Genera un profilo piatto e un grafico delle chiamate (output predefinito):

`sprof {{percorso/della/libreria.so}} {{percorso/della/libreria.so.profile}}`

- Genera un profilo piatto con conteggi e tick:

`sprof {{[-p|--flat-profile]}} {{percorso/della/libreria.so}} {{percorso/della/libreria.so.profile}}`

- Genera un grafico delle chiamate:

`sprof {{[-q|--graph]}} {{percorso/della/libreria.so}} {{percorso/della/libreria.so.profile}}`

- Stampa le coppie di chiamate e i loro conteggi di utilizzo:

`sprof {{[-c|--call-pairs]}} {{percorso/della/libreria.so}} {{percorso/della/libreria.so.profile}}`

- Usa i dati di profilazione dalla directory corrente (rilevati automaticamente dal soname):

`sprof {{percorso/della/libreria.so}}`
