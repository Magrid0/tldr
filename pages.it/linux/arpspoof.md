# arpspoof

> Falsifica risposte ARP per intercettare pacchetti.
> Maggiori informazioni: <https://manned.org/arpspoof>.

- Avvelena tutti gli host per intercettare pacchetti sull'[i]nterfaccia per l'host:

`sudo arpspoof -i {{wlan0}} {{ip_host}}`

- Avvelena il [t]arget per intercettare pacchetti sull'[i]nterfaccia per l'host:

`sudo arpspoof -i {{wlan0}} -t {{ip_target}} {{ip_host}}`

- Avvelena sia il [t]arget che l'host per intercettare pacchetti sull'[i]nterfaccia per l'host:

`sudo arpspoof -i {{wlan0}} -r -t {{ip_target}} {{ip_host}}`
