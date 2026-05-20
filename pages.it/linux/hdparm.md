# hdparm

> Ottiene e imposta parametri di hard disk SATA e IDE.
> Maggiori informazioni: <https://manned.org/hdparm>.

- Richiede le informazioni di identificazione di un dato dispositivo:

`sudo hdparm -I {{/dev/device}}`

- Ottiene il livello di Advanced Power Management:

`sudo hdparm -B {{/dev/device}}`

- Imposta il valore di Advanced Power Management (i valori 1-127 consentono lo spin-down, mentre i valori 128-254 non lo consentono):

`sudo hdparm -B {{1}} {{/dev/device}}`

- Mostra lo stato corrente della modalità di alimentazione del dispositivo:

`sudo hdparm -C {{/dev/device}}`

- Forza un'unità a entrare immediatamente in modalità standby (di solito causa lo spin-down dell'unità):

`sudo hdparm -y {{/dev/device}}`

- Mette l'unità in modalità idle (basso consumo), impostando anche il suo timeout di standby:

`sudo hdparm -S {{standby_timeout}} {{device}}`

- Testa la velocità di lettura di un dispositivo specifico:

`sudo hdparm -tT {{device}}`
