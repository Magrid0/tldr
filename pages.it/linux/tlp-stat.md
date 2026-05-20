# tlp-stat

> Genera rapporti sullo stato di TLP.
> Vedi anche: `tlp`.
> Maggiori informazioni: <https://linrunner.de/tlp/usage/tlp-stat>.

- Genera un rapporto sullo stato con la configurazione e tutte le impostazioni attive:

`sudo tlp-stat`

- Mostra informazioni su vari dispositivi:

`sudo tlp-stat --{{battery|disk|processor|graphics|pcie|rfkill|usb}}`

- Mostra informazioni dettagliate sui dispositivi che supportano la verbosità:

`sudo tlp-stat {{[-v|--verbose]}} --{{battery|processor|pcie|usb}}`

- Mostra la configurazione:

`sudo tlp-stat {{[-c|--config]}}`

- Monitora gli [ev]enti `udev` dell'alimentazione:

`sudo tlp-stat {{[-P|--pev]}}`

- Mostra la diagnostica dell'alimentazione:

`sudo tlp-stat --psup`

- Mostra [t]emperature e velocità della ventola:

`sudo tlp-stat {{[-t|--temp]}}`

- Mostra informazioni generali sul sistema:

`sudo tlp-stat {{[-s|--system]}}`
