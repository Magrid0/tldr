# iptables-save

> Salva la configurazione IPv4 di `iptables`.
> Usa `ip6tables-save` per fare lo stesso per IPv6.
> Maggiori informazioni: <https://manned.org/iptables-save>.

- Stampa la configurazione di `iptables`:

`sudo iptables-save`

- Stampa la configurazione di `iptables` di una tabella specifica:

`sudo iptables-save {{[-t|--table]}} {{table}}`

- Salva la configurazione di `iptables` in un file:

`sudo iptables-save {{[-f|--file]}} {{path/to/file}}`
