# braa

> Scanner SNMP di massa ultra veloce che permette più host simultaneamente.
> Maggiori informazioni: <https://manned.org/braa>.

- Cammina l'albero SNMP di un host con stringa public interrogando tutti gli OID sotto `.1.3.6`:

`braa public@{{ip_address}}:{{.1.3.6.*}}`

- Interroga l'intera sottorete `ip_range` per `system.sysLocation.0`:

`braa public@{{ip_range}}:{{.1.3.6.1.2.1.1.6.0}}`

- Tenta di impostare il valore di `system.sysLocation.0` a un workgroup specifico:

`braa private@{{ip_address}}:{{.1.3.6.1.2.1.1.6.0}}=s'{{workgroup}}'`
