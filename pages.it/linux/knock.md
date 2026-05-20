# knock

> Client di port knocking per aprire porte specifiche sul firewall.
> Maggiori informazioni: <https://manned.org/knock>.

- Esegue il knock sulle porte usando protocolli diversi:

`knock {{hostname}} {{portnumber}}:{{protocol}}`

- Esegue il knock su una porta usando UDP:

`knock {{[-u|--udp]}} {{hostname}} {{portnumber}}`

- Forza l'uso di IPv4/IPv6:

`knock {{-4|-6}} {{hostname}} {{portnumber}}`

- Mostra errori e dettagli della connessione:

`knock {{[-v|--verbose]}} {{hostname}} {{portnumber}}`
