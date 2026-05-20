# vso

> Gestore di pacchetti, aggiornatore di sistema e automatizzatore di attività per Vanilla OS.
> Maggiori informazioni: <https://github.com/Vanilla-OS/vanilla-system-operator>.

- Verifica la presenza di aggiornamenti di sistema per il sistema host:

`vso sys-upgrade check`

- Aggiorna subito il sistema host:

`vso sys-upgrade upgrade --now`

- Inizializza il sottosistema Pico (usato per la gestione dei pacchetti):

`vso pico-init`

- Installa applicazioni all'interno del sottosistema:

`vso install {{pacchetto1 pacchetto2 ...}}`

- Rimuovi applicazioni dal sottosistema:

`vso remove {{pacchetto1 pacchetto2 ...}}`

- Entra nella shell del sottosistema:

`vso shell`

- Esegui un'applicazione dal sottosistema:

`vso run {{pacchetto}}`

- Mostra la configurazione VSO:

`vso config show`
