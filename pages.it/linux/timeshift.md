# timeshift

> Utility di ripristino del sistema.
> Maggiori informazioni: <https://manned.org/timeshift>.

- Elenca gli snapshot:

`sudo timeshift --list`

- Crea un nuovo snapshot (se programmato):

`sudo timeshift --check`

- Crea un nuovo snapshot (anche se non programmato):

`sudo timeshift --create`

- Ripristina uno snapshot (selezionando interattivamente quale snapshot ripristinare):

`sudo timeshift --restore`

- Ripristina uno snapshot specifico:

`sudo timeshift --restore --snapshot '{{snapshot}}'`

- Elimina uno snapshot specifico:

`sudo timeshift --delete --snapshot '{{snapshot}}'`
