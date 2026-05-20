# fwupdmgr

> Aggiorna il firmware dei dispositivi, incluso UEFI, utilizzando `fwupd`.
> Vedi anche: `fwupdtool`.
> Maggiori informazioni: <https://github.com/fwupd/fwupd/blob/main/src/fwupdmgr.md>.

- Mostra tutti i dispositivi rilevati da `fwupd`:

`fwupdmgr get-devices`

- Scarica gli ultimi metadati del firmware da LVFS:

`fwupdmgr refresh`

- Elenca gli aggiornamenti disponibili per i dispositivi sul sistema:

`fwupdmgr get-updates`

- Installa gli aggiornamenti del firmware:

`fwupdmgr update`

- Rimonta `/boot` con più privilegi se l'aggiornamento segnala un filesystem in sola lettura:

`sudo mount {{[-o|--options]}} uid=1000,gid=1000,umask=0022 {{/dev/sdX}} /boot`

- Mostra la cronologia degli aggiornamenti del firmware:

`fwupdmgr get-history`
