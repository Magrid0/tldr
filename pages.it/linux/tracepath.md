# tracepath

> Traccia il percorso verso un host di rete scoprendo l'MTU lungo questo percorso.
> Maggiori informazioni: <https://manned.org/tracepath>.

- Un modo consigliato per tracciare il percorso verso un host:

`tracepath -p {{33434}} {{host}}`

- Specifica la porta di destinazione iniziale, utile con impostazioni firewall non standard:

`tracepath -p {{porta_destinazione}} {{host}}`

- Stampa sia i nomi host che gli indirizzi IP numerici:

`tracepath -b {{host}}`

- Specifica un TTL massimo (numero di hop):

`tracepath -m {{hop_max}} {{host}}`

- Specifica la lunghezza iniziale del pacchetto (default 65535 per IPv4 e 128000 per IPv6):

`tracepath -l {{lunghezza_pacchetto}} {{host}}`

- Utilizza solo indirizzi IPv6:

`tracepath -6 {{host}}`
