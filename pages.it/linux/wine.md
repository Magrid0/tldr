# wine

> Esegue eseguibili Windows su sistemi basati su Unix.
> Maggiori informazioni: <https://gitlab.winehq.org/wine/wine/-/wikis/Commands>.

- Esegue un programma specifico all'interno dell'ambiente `wine`:

`wine {{comando}}`

- Esegue un programma specifico in background:

`wine start {{comando}}`

- Installa/disinstalla un pacchetto MSI:

`wine msiexec /{{i|x}} {{percorso/del/pacchetto.msi}}`

- Esegue `Esplora file`, `Blocco note` o `WordPad`:

`wine {{explorer|notepad|write}}`

- Esegue `Editor del Registro di sistema`, `Pannello di controllo` o `Task Manager`:

`wine {{regedit|control|taskmgr}}`

- Apre un desktop Wine virtuale:

`wine explorer /desktop={{shell}},{{1920x1080}}`

- Esegue lo strumento di configurazione:

`wine winecfg`

- Aggiunge una chiave del registro:

`wine reg add '{{percorso\della\chiave_registro}}' /v {{Nome_valore}} /t {{REG_SZ|REG_BINARY|REG_DWORD|...}} /d '{{dati}}'`
