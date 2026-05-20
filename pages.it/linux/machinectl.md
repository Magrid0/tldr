# machinectl

> Controlla il gestore di macchine di systemd.
> Esegue operazioni su macchine virtuali, container e immagini.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/machinectl.html>.

- Avvia una macchina come servizio usando `systemd-nspawn`:

`sudo machinectl start {{machine_name}}`

- Ferma una macchina in esecuzione:

`sudo machinectl stop {{machine_name}}`

- Mostra un elenco delle macchine in esecuzione:

`machinectl list`

- Apre una shell interattiva all'interno della macchina:

`sudo machinectl shell {{machine_name}}`
