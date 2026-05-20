# cryptcat

> Cryptcat è netcat con capacità di crittografia.
> Maggiori informazioni: <https://manned.org/cryptcat>.

- [l]Ascolta su una [p]orta specifica e stampa tutti i dati ricevuti:

`cryptcat -k {{password}} -l -p {{port}}`

- Si connette a una porta specifica:

`cryptcat -k {{password}} {{ip_address}} {{port}}`

- Specifica il timeout ([w]):

`cryptcat -k {{password}} -w {{timeout_in_seconds}} {{ip_address}} {{port}}`

- Scansiona ([z]) le porte aperte di un host specifico:

`cryptcat -v -z {{ip_address}} {{port}}`

- Agisce come proxy e inoltra i dati da una porta TCP locale a un host remoto specificato:

`cryptcat -k {{password}} -l -p {{local_port}} | cryptcat -k {{password}} {{hostname}} {{remote_port}}`
