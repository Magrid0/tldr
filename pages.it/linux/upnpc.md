# upnpc

> Configura le regole di inoltro delle porte sul router tramite il protocollo UPnP.
> Maggiori informazioni: <https://manned.org/upnpc>.

- Inoltra la porta TCP esterna 80 alla porta 8080 su una macchina locale:

`upnpc -a {{192.168.0.1}} 8080 80 tcp`

- Elimina qualsiasi reindirizzamento della porta TCP esterna 80:

`upnpc -d 80 tcp`

- Ottieni informazioni sui dispositivi UPnP sulla rete:

`upnpc -s`

- Elenca i reindirizzamenti esistenti:

`upnpc -l`
