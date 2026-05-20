# tod

> Un piccolo client Todoist in Rust.
> Accetta input semplici e li inserisce nella tua casella di posta o in un altro progetto, sfruttando l'elaborazione del linguaggio naturale per assegnare date di scadenza, tag, ecc.
> Maggiori informazioni: <https://github.com/tod-org/tod/blob/main/docs/usage.md#usage>.

- Importa i tuoi progetti (necessario per abilitare i prompt dei progetti):

`tod project import`

- Crea rapidamente un'attività con data di scadenza:

`tod --quickadd {{Compra più latte oggi}}`

- Crea una nuova attività (verrà richiesto contenuto e progetto):

`tod task create`

- Crea un'attività in un progetto:

`tod task create --content "{{Scrivi più rust}}" --project {{codice}}`

- Ottieni la prossima attività per un progetto:

`tod task next`

- Ottieni il tuo programma di lavoro:

`tod task list --scheduled --project {{lavoro}}`

- Ottieni tutte le attività per lavoro:

`tod task list --project {{lavoro}}`
