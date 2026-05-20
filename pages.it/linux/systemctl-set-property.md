# systemctl set-property

> Imposta le proprietà specificate dell'unità in fase di esecuzione.
> Vedi anche: `systemctl revert`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#set-property%20UNIT%20PROPERTY=VALUE%E2%80%A6>.

- Imposta una proprietà per un servizio in esecuzione:

`systemctl set-property {{unità}} {{proprietà}}={{valore}}`

- Imposta più proprietà contemporaneamente:

`systemctl set-property {{unità}} {{proprietà_1=valore_1 proprietà_2=valore_2 ...}}`

- Imposta una proprietà solo per la sessione runtime corrente (non persistente):

`systemctl set-property {{unità}} {{proprietà}}={{valore}} --runtime`

- Reimposta una proprietà al suo valore predefinito:

`systemctl set-property {{unità}} {{proprietà}}=`

- Reimposta più proprietà ai loro valori predefiniti:

`systemctl set-property {{unità}} {{proprietà_1= proprietà_2= ...}}`
