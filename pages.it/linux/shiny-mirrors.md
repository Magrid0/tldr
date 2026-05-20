# shiny-mirrors

> Genera un mirror list di `pacman` per Manjaro Linux.
> Ogni esecuzione di shiny-mirrors richiede di sincronizzare il database e aggiornare il sistema usando `sudo pacman -Syyu`.
> Maggiori informazioni: <https://gitlab.com/Arisa_Snowbell/shiny-mirrors/-/blob/domina/shiny-mirrors/man/shiny-mirrors.md>.

- Ottiene lo stato dei mirror correnti:

`shiny-mirrors status`

- Genera un mirror list usando il comportamento predefinito:

`sudo shiny-mirrors refresh`

- Mostra il file di configurazione corrente:

`shiny-mirrors config show`

- Passa a un branch differente in modo interattivo:

`sudo shiny-mirrors config --branch`
