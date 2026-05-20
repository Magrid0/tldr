# owut

> OpenWrt Upgrade Tool per automatizzare build e installazioni tramite Attended SysUpgrade (ASU).
> Maggiori informazioni: <https://openwrt.org/docs/guide-user/installation/sysupgrade.owut>.

- Elenca le versioni disponibili di OpenWrt per il dispositivo corrente:

`owut versions`

- Elenca i pacchetti installati o rimossi dall'utente:

`owut list`

- Controlla la presenza di aggiornamenti senza eseguire un aggiornamento:

`owut check`

- Costruisce, scarica, verifica e installa automaticamente l'ultimo firmware disponibile:

`owut upgrade`

- Aggiorna a una versione specifica e include pacchetti aggiuntivi:

`owut upgrade {{[-V|--version-to]}} {{versione}} {{[-a|--add]}} "{{htop vim}}"`

- Scarica e verifica un'immagine specifica senza installarla:

`owut download {{[-V|--version-to]}} {{25.12.0}}`

- Verifica l'ultima immagine scaricata e la installa (il dispositivo si riavvierà):

`owut install`
