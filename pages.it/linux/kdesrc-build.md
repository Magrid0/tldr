# kdesrc-build

> Compila facilmente componenti KDE dai repository sorgente.
> Maggiori informazioni: <https://manned.org/kdesrc-build>.

- Inizializza `kdesrc-build`:

`kdesrc-build --initial-setup`

- Compila un componente KDE e le sue dipendenze dal sorgente:

`kdesrc-build {{component_name}}`

- Compila un componente senza aggiornare il suo codice locale e senza compilare le sue dipendenze:

`kdesrc-build --no-src --no-include-dependencies {{component_name}}`

- Aggiorna le directory di build prima di compilare:

`kdesrc-build --refresh-build {{component_name}}`

- Riprende la compilazione da una dipendenza specifica:

`kdesrc-build --resume-from {{dependency_component}} {{component_name}}`

- Esegue un componente con un nome di eseguibile specificato:

`kdesrc-build --run --exec {{executable_name}} {{component_name}}`

- Compila tutti i componenti configurati:

`kdesrc-build`

- Usa le librerie di sistema al posto di un componente se la compilazione fallisce:

`kdesrc-build --no-stop-on-failure {{component_name}}`
