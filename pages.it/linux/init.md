# init

> Gestore dei runlevel di Linux.
> Richiede l'opzione di compilazione SYSVINIT abilitata se si utilizza systemd.
> Maggiori informazioni: <https://manned.org/init.8>.

- Imposta il sistema per eseguire un ambiente grafico:

`sudo init 5`

- Imposta il sistema per eseguire il terminale multiutente:

`sudo init 3`

- Spegne il sistema:

`init 0`

- Riavvia il sistema:

`init 6`

- Imposta il sistema per l'esecuzione in terminale con solo l'utente root consentito e senza rete:

`sudo init 1`
