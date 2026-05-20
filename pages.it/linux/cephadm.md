# cephadm

> Distribuisce e gestisce un cluster Ceph utilizzando container.
> Parte del framework di orchestrazione Ceph.
> Maggiori informazioni: <https://docs.ceph.com/en/latest/man/8/cephadm/>.

- Avvia un nuovo cluster Ceph sull'host corrente:

`sudo cephadm bootstrap --mon-ip {{monitor_ip}}`

- Aggiunge un nuovo host al cluster:

`sudo cephadm add-host {{hostname}} {{ip_address}}`

- Distribuisce un servizio specifico (ad es. mgr, mon, osd):

`sudo cephadm deploy {{service_type}} --name {{service_name}}`

- Verifica lo stato dei servizi del cluster:

`sudo cephadm shell -- ceph {{[-s|--status]}}`

- Accede a un ambiente shell all'interno del container Ceph:

`sudo cephadm shell`

- Rimuove un servizio dal cluster:

`sudo cephadm rm-service {{service_type}} --name {{service_name}}`
