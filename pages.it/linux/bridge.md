# bridge

> Mostra e manipola indirizzi e dispositivi dei bridge di rete.
> Maggiori informazioni: <https://manned.org/bridge>.

- Elenca tutti i bridge e le loro interfacce:

`bridge {{[l|link]}}`

- Mostra informazioni VLAN delle porte:

`bridge {{[v|vlan]}}`

- Assegna una VLAN a una porta:

`sudo bridge {{[v|vlan]}} {{[a|add]}} dev {{lanX}} vid {{vlan_id}} pvid {{tagged|untagged}}`

- Rimuove una VLAN da una porta:

`sudo bridge {{[v|vlan]}} {{[d|delete]}} dev {{lanX}} vid {{vlan_id}}`

- Osserva le modifiche nelle interfacce bridge:

`bridge {{[mo|monitor]}}`

- Mostra aiuto:

`bridge {{[h|help]}}`
