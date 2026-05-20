# openfortivpn

> Un client VPN per la soluzione VPN proprietaria PPP+SSL di Fortinet.
> Maggiori informazioni: <https://manned.org/openfortivpn>.

- Si connette a una VPN con nome utente e password:

`openfortivpn {{[-u|--username]}} {{nome_utente}} {{[-p|--password]}} {{password}}`

- Si connette a una VPN usando un file di configurazione specifico (predefinito `/etc/openfortivpn/config`):

`sudo openfortivpn {{[-c|--config]}} {{percorso/del/config}}`

- Si connette a una VPN specificando host e porta:

`openfortivpn {{host}}:{{porta}}`

- Fida di un dato gateway passando la somma sha256 del suo certificato:

`openfortivpn --trusted-cert {{sha256_sum}}`
