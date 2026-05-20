# ego

> Lo strumento ufficiale di gestione della personalità di sistema di Funtoo.
> Maggiori informazioni: <https://funtoo-ego.readthedocs.io/en/develop/>.

- Sincronizza l'albero di Portage:

`ego sync`

- Aggiorna la configurazione del bootloader:

`ego boot update`

- Legge una pagina wiki di Funotto per nome:

`ego doc {{pagina_wiki}}`

- Mostra il profilo corrente:

`ego profile show`

- Abilita/Disabilita mix-in:

`ego profile mix-in +{{gnome}} -{{kde-plasma-5}}`

- Interroga i bug di Funtoo relativi a un pacchetto specificato:

`ego query bug {{pacchetto}}`
