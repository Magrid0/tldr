# aur sync

> Scarica e costruisce automaticamente pacchetti AUR.
> Nota: è necessario definire un repository locale in `/etc/pacman.conf` e installare `vifm` per il funzionamento completo.
> Maggiori informazioni: <https://github.com/aurutils/aurutils>.

- Scarica uno o più pacchetti e le loro dipendenze dall'AUR, li costruisce e li aggiunge a un repository locale:

`aur sync {{pacchetto1 pacchetto2 ...}}`

- Aggiorna i pacchetti del repository locale:

`aur sync {{[-u|--upgrades]}}`

- Pulisce i file di build dopo l'installazione:

`aur sync {{[-C|--clean]}} {{pacchetto}}`

- Installa un pacchetto senza visualizzare le modifiche in Vim e senza confermare l'installazione delle dipendenze:

`aur sync --noview {{[-n|--noconfirm]}} {{pacchetto}}`

- Ignora pacchetti specifici durante l'aggiornamento:

`aur sync {{[-u|--upgrades]}} --ignore {{pacchetto1,pacchetto2,...}}`
