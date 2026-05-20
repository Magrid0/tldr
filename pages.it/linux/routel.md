# routel

> Elenca il routing IP in un formato leggibile.
> Vedi anche: `ip route`, `route`.
> Maggiori informazioni: <https://manned.org/routel>.

- Mostra la tabella di routing predefinita:

`routel`

- Mostra una tabella di routing specifica:

`routel {{table_number|main|local|default}}`

- Mostra solo le route IPv4:

`routel {{[-4|--family inet]}}`

- Mostra solo le route IPv6:

`routel {{[-6|--family inet6]}}`
