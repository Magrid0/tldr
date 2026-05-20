# rdesktop

> Client del protocollo Remote Desktop.
> Può essere usato per connettersi a un computer remoto usando il protocollo RDP.
> Maggiori informazioni: <https://manned.org/rdesktop>.

- Si connette a un computer remoto (la porta predefinita è 3389):

`rdesktop -u {{username}} -p {{password}} {{host:port}}`

- Esempi semplici:

`rdesktop -u Administrator -p passwd123 192.168.1.111:3389`

- Si connette a un computer remoto a schermo intero (premi `<Ctrl Alt Enter>` per uscire):

`rdesktop -u {{username}} -p {{password}} -f {{host:port}}`

- Usa una risoluzione personalizzata (usa la lettera `x` tra i numeri):

`rdesktop -u {{username}} -p {{password}} -g {{1366}}x{{768}} {{host:port}}`

- Si connette a un computer remoto usando un utente di dominio:

`rdesktop -u {{username}} -p {{password}} -d {{domainname}} {{host:port}}`

- Usa il colore a 16 bit (più veloce):

`rdesktop -u {{username}} -p {{password}} -a 16 {{host:port}}`
