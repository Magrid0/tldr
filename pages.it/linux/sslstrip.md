# sslstrip

> Esegue gli attacchi di stripping SSL (Secure Sockets Layer) di Moxie Marlinspike.
> Esegue un attacco ARP spoofing in concomitanza.
> Maggiori informazioni: <https://www.kali.org/tools/sslstrip/>.

- Registra solo il traffico HTTPS POST sulla porta 10000 per impostazione predefinita:

`sslstrip`

- Registra solo il traffico HTTPS POST sulla porta 8080:

`sslstrip --listen={{8080}}`

- Registra tutto il traffico SSL da e verso il server sulla porta 8080:

`sslstrip --ssl --listen={{8080}}`

- Registra tutto il traffico SSL e HTTP da e verso il server sulla porta 8080:

`sslstrip --listen={{8080}} --all`

- Specifica il percorso del file in cui salvare i log:

`sslstrip --listen={{8080}} --write={{percorso/del/file}}`

- Mostra aiuto:

`sslstrip --help`
