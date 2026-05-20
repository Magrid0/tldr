# rnm

> Utilità di rinomina in blocco.
> Maggiori informazioni: <https://github.com/neurobin/rnm#basic-options>.

- Sostituisce una stringa di ricerca con una stringa di sostituzione nei nomi dei file:

`rnm -ss {{old}} -rs {{new}} {{path/to/directory}}`

- Usa una stringa di ricerca e sostituzione fissa (letterale) invece di `regex`:

`rnm -ssf {{old}} -rs {{new}} {{path/to/files}}`

- Aggiunge un indice incrementato automaticamente ai nomi dei file a partire da 1:

`rnm -i 1 -inc 1 -rs {{_}} {{path/to/files}}`

- Rinomina i file usando un elenco di nuovi nomi da un file di testo:

`rnm -ns/f {{path/to/names.txt}} {{path/to/files}}`

- Rinomina solo i file (ignorando directory e link):

`rnm -fo -ss {{pattern}} -rs {{replacement}} {{path/to/files}}`

- Ordina i file di input per data di modifica prima di rinominare:

`rnm -s/mt -ss {{pattern}} -rs {{replacement}} {{path/to/files}}`

- Esegue una simulazione senza apportare modifiche effettive:

`rnm -sim -ss {{pattern}} -rs {{replacement}} {{path/to/files}}`

- Annulla l'ultima operazione di rinomina:

`rnm -u`
