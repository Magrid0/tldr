# keyd

> Rimappa i tasti.
> Maggiori informazioni: <https://manned.org/keyd>.

- Avvia e abilita il servizio `keyd`:

`systemctl enable keyd --now`

- Mostra informazioni sulla pressione dei tasti:

`sudo keyd {{[-m|monitor]}}`

- Reimposta i binding e ricarica i file di configurazione in `/etc/keyd`:

`sudo keyd reload`

- Elenca tutti i nomi di tasti validi:

`keyd list-keys`

- Controlla la presenza di errori nei file di configurazione rilevati:

`keyd check`

- Crea un binding temporaneo:

`sudo keyd bind "{{pressed_key}} = {{output_key}}"`
