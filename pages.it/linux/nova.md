# nova

> Il progetto OpenStack che fornisce un modo per fornire istanze di calcolo.
> Maggiori informazioni: <https://docs.openstack.org/nova/latest/>.

- Elenca le VM sul tenant corrente:

`nova list`

- Elenca le VM di tutti i tenant (solo utente amministratore):

`nova list --all-tenants`

- Avvia una VM su un host specifico:

`nova boot --nic net-id={{id_rete}} --image {{id_immagine}} --flavor {{flavor}} --availability-zone nova:{{nome_host}} {{nome_vm}}`

- Avvia un server:

`nova start {{server}}`

- Ferma un server:

`nova stop {{server}}`

- Collega un'interfaccia di rete a una VM specifica:

`nova interface-attach --net-id {{id_rete}} {{server}}`
