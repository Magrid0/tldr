# emaint

> Esegue attività di manutenzione di Portage.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Portage#emaint>.

- Sincronizza i repository impostati per la sincronizzazione automatica (predefinito per la maggior parte dei repository):

`sudo emaint sync {{[-a|--auto]}}`

- Sincronizza un repository specifico:

`sudo emaint sync {{[-r|--repo]}} {{repository}}`

- Sincronizza tutti i repository:

`sudo emaint sync {{[-A|--allrepos]}}`

- Pulisce l'elenco di ripresa di Portage:

`sudo emaint cleanresume {{[-f|--fix]}}`

- Pulisce i log di Portage:

`sudo emaint logs {{[-C|--clean]}}`
