# named

> Esegue il demone del server DNS (Dynamic Name Service) che converte nomi host in indirizzi IP e viceversa.
> Maggiori informazioni: <https://manned.org/named>.

- Legge il file di configurazione predefinito `/etc/named.conf`, legge eventuali dati iniziali e resta in ascolto per query:

`named`

- Legge un file di configurazione personalizzato:

`named -c {{percorso/del/named.conf}}`

- Usa solo IPv4 o IPv6, anche se la macchina host è in grado di utilizzare altri protocolli:

`named {{-4|-6}}`

- Ascolta le query su una porta specifica invece della porta predefinita 53:

`named -p {{porta}}`

- Esegue il server in primo piano senza demone:

`named -f`
