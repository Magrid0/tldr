# portageq

> Interroga informazioni su Portage, il gestore pacchetti di Gentoo Linux.
> Le variabili d'ambiente specifiche di Portage interrogabili sono elencate in `/var/db/repos/gentoo/profiles/info_vars`.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Portageq>.

- Mostra il valore di una variabile d'ambiente specifica di Portage:

`portageq envvar {{variabile}}`

- Mostra un elenco dettagliato dei repository configurati con Portage:

`portageq repos_config /`

- Mostra un elenco di repository ordinati per priorità (più alto per primo):

`portageq get_repos /`

- Mostra un metadato specifico su un atom (es. nome del pacchetto inclusa la versione):

`portageq metadata / {{ebuild|porttree|binary|...}} {{categoria}}/{{pacchetto}} {{BDEPEND|DEFINED_PHASES|DEPEND|...}}`
