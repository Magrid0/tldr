# torsocks

> Instrada il traffico di qualsiasi applicazione attraverso la rete Tor.
> Nota: `torsocks` presuppone di doversi connettere al proxy SOCKS Tor in esecuzione su 127.0.0.1:9050, che sono le impostazioni predefinite del demone Tor.
> Maggiori informazioni: <https://manned.org/torsocks>.

- Esegui un comando usando Tor:

`torsocks {{comando}}`

- Abilita o disabilita Tor in questa shell:

`. torsocks {{on|off}}`

- Avvia una nuova shell abilitata a Tor:

`torsocks --shell`

- Verifica se la shell corrente è abilitata a Tor (il valore di `$LD_PRELOAD` sarà vuoto se disabilitato):

`torsocks show`

- Isola il traffico attraverso un circuito Tor diverso, migliorando l'anonimato:

`torsocks {{[-i|--isolate]}} {{curl https://check.torproject.org/api/ip}}`

- Connettiti a un proxy Tor in esecuzione su un indirizzo e porta specifici:

`torsocks {{[-a|--address]}} {{indirizzo_ip}} {{[-P|--port]}} {{porta}} {{comando}}`
