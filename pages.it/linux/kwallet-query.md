# kwallet-query

> Legge e scrive in un Portafoglio KDE.
> Maggiori informazioni: <https://manned.org/kwallet-query>.

- Elenca tutte le voci nella cartella `Passwords` di `kdewallet`:

`kwallet-query {{kdewallet}} {{[-l|--list-entries]}}`

- Elenca tutte le voci in una cartella specifica:

`kwallet-query {{kdewallet}} {{[-l|--list-entries]}} {{[-f|--folder]}} {{folder_name}}`

- Elenca tutte le cartelle disponibili:

`kwallet-query {{kdewallet}} {{[-l|--list-entries]}} {{[-f|--folder]}} ""`

- Mostra aiuto:

`kwallet-query {{[-h|--help]}}`
