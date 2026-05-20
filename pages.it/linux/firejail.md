# firejail

> Sandbox sicuri per i processi utilizzando le funzionalità Linux integrate.
> Maggiori informazioni: <https://manned.org/firejail>.

- Integra firejail con l'ambiente desktop:

`sudo firecfg`

- Apre una istanza ristretta di Mozilla Firefox:

`firejail {{firefox}}`

- Avvia un server Apache ristretto su un'interfaccia e indirizzo noti:

`firejail --net={{eth0}} --ip={{192.168.1.244}} {{/etc/init.d/apache2}} {{start}}`

- Elenca i sandbox in esecuzione:

`firejail --list`

- Elenca l'attività di rete dei sandbox in esecuzione:

`firejail --netstats`

- Arresta un sandbox in esecuzione:

`firejail --shutdown={{7777}}`

- Esegue una sessione Firefox ristretta per navigare su Internet:

`firejail --seccomp --private --private-dev --private-tmp --protocol=inet firefox --new-instance --no-remote --safe-mode --private-window`

- Utilizza un file hosts personalizzato (sovrascrive il file `/etc/hosts`):

`firejail --hosts-file={{~/myhosts}} {{curl http://mysite.arpa}}`
