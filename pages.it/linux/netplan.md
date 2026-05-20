# netplan

> Utilità di configurazione di rete che utilizza YAML.
> Maggiori informazioni: <https://netplan.readthedocs.io/en/stable/cli/>.

- Applica una configurazione di rete e la rende persistente:

`sudo netplan apply`

- Genera i file di configurazione del backend:

`sudo netplan generate`

- Configura un'interfaccia di rete per utilizzare DHCP:

`sudo netplan set ethernets.{{nome_interfaccia}}.dhcp4=true`

- Prova le modifiche di configurazione senza applicarle permanentemente:

`sudo netplan try --timeout {{secondi}}`

- Torna alla configurazione funzionante precedente dopo un'applicazione fallita:

`sudo netplan --debug apply`

- Mostra lo stato corrente della configurazione netplan:

`netplan status`
