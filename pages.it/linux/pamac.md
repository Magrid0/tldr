# pamac

> Utilità per il gestore pacchetti GUI pamac.
> Se non riesci a vedere i pacchetti AUR, abilitalo in `/etc/pamac.conf` o nella GUI.
> Maggiori informazioni: <https://wiki.manjaro.org/index.php/Pamac>.

- Installa un nuovo pacchetto:

`pamac install {{nome_pacchetto}}`

- Rimuovi un pacchetto e le sue dipendenze non più necessarie (orfane):

`pamac remove --orphans {{nome_pacchetto}}`

- Cerca nel database dei pacchetti un pacchetto:

`pamac search {{nome_pacchetto}}`

- Elenca i pacchetti installati:

`pamac list --installed`

- Controlla la presenza di aggiornamenti:

`pamac checkupdates`

- Aggiorna tutti i pacchetti:

`pamac upgrade`
