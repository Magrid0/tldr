# euse

> Abilita, disabilita e ottiene informazioni sui flag USE di Gentoo.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Euse>.

- Elenca i flag USE globali attivi:

`euse {{[-a|--active]}} {{[-g|--global]}}`

- Elenca i flag USE locali attivi:

`euse {{[-a|--active]}} {{[-l|--local]}}`

- Abilita un flag USE globale:

`sudo euse {{[-E|--enable]}} {{flag_use}}`

- Disabilita un flag USE globale (mettere un segno '-' davanti al flag USE):

`sudo euse {{[-D|--disable]}} {{flag_use}}`

- Rimuove un flag USE globale:

`sudo euse {{[-P|--prune]}} {{flag_use}}`
