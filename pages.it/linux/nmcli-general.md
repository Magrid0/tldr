# nmcli general

> Gestisce le impostazioni generali di NetworkManager.
> Maggiori informazioni: <https://networkmanager.pages.freedesktop.org/NetworkManager/NetworkManager/nmcli.html#general>.

- Mostra lo stato generale di NetworkManager:

`nmcli {{[g|general]}}`

- Mostra il nome host del dispositivo corrente:

`nmcli {{[g|general]}} {{[h|hostname]}}`

- Cambia il nome host del dispositivo corrente:

`sudo nmcli {{[g|general]}} {{[h|hostname]}} {{nuovo_nome_host}}`

- Mostra i permessi di NetworkManager:

`nmcli {{[g|general]}} {{[p|permissions]}}`

- Mostra il livello di logging e i domini correnti:

`nmcli {{[g|general]}} {{[l|logging]}}`

- Imposta il livello di logging e/o i domini (vedi `man NetworkManager.conf` per tutti i domini disponibili):

`sudo nmcli {{[g|general]}} {{[l|logging]}} {{[l|level]}} {{INFO|OFF|ERR|WARN|DEBUG|TRACE}} domain {{dominio_1,dominio_2,...}}`
