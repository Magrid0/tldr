# ipmitool

> Interfaccia con l'Intelligent Platform Management Interface (IPMI).
> Maggiori informazioni: <https://manned.org/ipmitool>.

- Avvia il driver IPMI per connessioni locali:

`systemctl start ipmidrv`

- Apre la shell IPMI sull'hardware locale:

`sudo ipmitool shell`

- Apre la shell IPMI su un host remoto:

`ipmitool -H {{ip_address}} -U {{user_name}} shell`
