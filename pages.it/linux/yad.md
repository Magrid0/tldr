# yad

> Mostra dialoghi GTK+ da script shell.
> Vedi anche: `zenity`.
> Maggiori informazioni: <https://manned.org/yad>.

- Mostra il contenuto di un file in un dialogo informativo di testo:

`yad --text-info --filename {{path/to/file}}`

- Apri un dialogo di inserimento testo e restituisci l'input su `stdout`:

`yad --entry --text "{{messaggio}}"`

- Apri un selettore di file con un titolo specifico:

`yad --file --title "{{messaggio_titolo}}"`

- Apri un dialogo di selezione data con un titolo specifico:

`yad --calendar --title "{{messaggio_titolo}}"`

- Mostra un dialogo a elenco con più colonne e dati:

`yad --list --column "{{col1}}" --column "{{col2}}" {{col1_riga1 col2_riga1 col1_riga2 col2_riga2 ...}}`

- Apri una barra di progresso pulsante che si chiude automaticamente al 100%:

`{{comando}} | yad --progress --pulsate --auto-close --text "{{messaggio}}"`
