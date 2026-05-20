# lsblk

> Elenca informazioni sui dispositivi.
> Maggiori informazioni: <https://manned.org/lsblk>.

- Elenca tutti i dispositivi di archiviazione in un formato ad albero:

`lsblk`

- Elenca anche i dispositivi vuoti:

`lsblk {{[-a|--all]}}`

- Stampa la colonna SIZE in byte invece che in formato leggibile dall'uomo:

`lsblk {{[-b|--bytes]}}`

- Mostra informazioni sui filesystem:

`lsblk {{[-f|--fs]}}`

- Usa caratteri ASCII per la formattazione ad albero:

`lsblk {{[-i|--ascii]}}`

- Mostra informazioni sulla topologia dei dispositivi a blocchi:

`lsblk {{[-t|--topology]}}`

- Esclude i dispositivi specificati dall'elenco separato da virgole dei numeri di dispositivo maggiori:

`lsblk {{[-e|--exclude]}} {{1,7,...}}`

- Aggiunge informazioni extra all'output usando un elenco separato da virgole di colonne (ometti il segno `+` per mostrare solo le colonne specificate):

`lsblk {{[-o|--output]}} +{{NAME,ROTA,SERIAL,MODEL,TRAN,TYPE,SIZE,FSTYPE,MOUNTPOINT,...}}`
