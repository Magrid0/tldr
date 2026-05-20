# kde-builder

> Compila facilmente componenti KDE dai repository sorgente.
> Sostituto diretto di `kdesrc-build`.
> Maggiori informazioni: <https://kde-builder.kde.org/en/cmdline/supported-cmdline-params.html>.

- Inizializza `kde-builder`:

`kde-builder --initial-setup`

- Compila un componente KDE e le sue dipendenze dal sorgente (usa `workspace` per compilare il desktop Plasma):

`kde-builder {{component_name1 component_name2 ...}}`

- Compila un componente senza aggiornare il suo codice locale e senza compilare le sue dipendenze:

`kde-builder {{[-SD|--no-src --no-include-dependencies]}} {{component_name}}`

- Aggiorna le directory di build prima di compilare:

`kde-builder {{[-r|--refresh-build]}} {{component_name}}`

- Riprende la compilazione da una dipendenza specifica:

`kde-builder {{[-f|--resume-from]}} {{dependency_component}} {{component_name}}`

- Esegue un componente con un nome di eseguibile specificato:

`kde-builder --run {{executable_name}}`

- Installa la sessione di login:

`kde-builder --install-login-session-only`

- Usa le librerie di sistema al posto di un componente se la compilazione fallisce:

`kde-builder --no-stop-on-failure {{component_name}}`
