# networkctl

> Interroga lo stato dei collegamenti di rete.
> Gestisce la configurazione di rete usando `systemd-networkd`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/networkctl.html>.

- Elenca i collegamenti esistenti con il loro stato:

`networkctl`

- Mostra lo stato complessivo della rete:

`networkctl status`

- Attiva i dispositivi di rete:

`networkctl up {{interfaccia1 interfaccia2 ...}}`

- Disattiva i dispositivi di rete:

`networkctl down {{interfaccia1 interfaccia2 ...}}`

- Rinnova le configurazioni dinamiche (es. indirizzi IP ricevuti da un server DHCP):

`networkctl renew {{interfaccia1 interfaccia2 ...}}`

- Ricarica i file di configurazione (`.netdev` e `.network`):

`networkctl reload`

- Riconfigura le interfacce di rete (se hai modificato la configurazione, devi prima chiamare `networkctl reload`):

`networkctl reconfigure {{interfaccia1 interfaccia2 ...}}`
