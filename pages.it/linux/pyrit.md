# pyrit

> Strumento di cracking WPA/WPA2 che utilizza potenza di calcolo.
> Maggiori informazioni: <https://manned.org/pyrit>.

- Mostra la velocità di cracking del sistema:

`pyrit benchmark`

- Elenca i core disponibili:

`pyrit list_cores`

- Imposta [E]SSID:

`pyrit -e "{{ESSID}}" create_essid`

- [l]egge e analizza un file di cattura pacchetti specifico:

`pyrit -r {{percorso/del/file.cap|percorso/del/file.pcap}} analyze`

- Legge e [i]mporta password nel database corrente:

`pyrit -i {{percorso/del/file}} {{import_unique_passwords|unique_passwords|import_passwords}}`

- Es[o]rta password dal database in un file specifico:

`pyrit -o {{percorso/del/file}} export_passwords`

- Traduce password con Pired Master Keys:

`pyrit batch`

- [l]egge il file di cattura e cracca la password:

`pyrit -r {{percorso/del/file}} attack_db`
