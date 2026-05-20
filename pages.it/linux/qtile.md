# qtile

> Un window manager a tiling completo e hackable scritto e configurato in Python.
> Maggiori informazioni: <https://docs.qtile.org/en/latest/manual/commands/shell/index.html>.

- Avvia il window manager, se non è già in esecuzione (dovrebbe idealmente essere eseguito da `.xsession` o simile):

`qtile start`

- Controlla il file di configurazione per eventuali errori di compilazione (la posizione predefinita è `~/.config/qtile/config.py`):

`qtile check`

- Mostra le informazioni correnti sull'utilizzo delle risorse:

`qtile top --force`

- Apre il programma `xterm` come finestra flottante sul gruppo chiamato `test-group`:

`qtile run-cmd --group {{test-group}} --float {{xterm}}`

- Riavvia il window manager:

`qtile cmd-obj --object cmd --function restart`
