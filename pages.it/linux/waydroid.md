# waydroid

> Un approccio basato su container per avviare un sistema Android completo su un sistema Linux regolare come Ubuntu.
> Maggiori informazioni: <https://docs.waydro.id/usage/waydroid-command-line-options>.

- Avvia Waydroid:

`waydroid show-full-ui`

- Inizializza Waydroid (richiesto al primo avvio o dopo la reinstallazione di Android):

`sudo waydroid init`

- Installa una nuova app Android da un file:

`waydroid app install {{percorso/del/file}}.apk`

- Avvia un'app Android tramite il nome del pacchetto:

`waydroid app launch {{com.example.app}}`

- Avvia o ferma la sessione Waydroid:

`waydroid session {{start|stop}}`

- Gestisci il contenitore Waydroid:

`sudo waydroid container {{start|stop|restart|freeze|unfreeze}}`

- Apri la shell Waydroid:

`sudo waydroid shell`

- Regola le dimensioni della finestra Waydroid:

`waydroid prop set persist.waydroid.{{width|height}} {{numero}}`
