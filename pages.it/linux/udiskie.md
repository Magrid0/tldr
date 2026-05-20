# udiskie

> Un auto-mounter a livello utente per supporti rimovibili che utilizza udisks2.
> Vedi anche: `udiskie-mount`, `udiskie-umount`.
> Maggiori informazioni: <https://github.com/coldfix/udiskie/wiki/Usage>.

- Avvia udiskie con icona nella barra delle applicazioni e notifiche:

`udiskie --tray --notify`

- Esegui udiskie senza usare un file di configurazione:

`udiskie --no-config`

- Specifica un file di configurazione personalizzato:

`udiskie --config {{percorso/del/config.yml}}`

- Usa un comando personalizzato per la richiesta di password:

`udiskie --password-prompt '{{comando}}'`

- Abilita l'output verboso:

`udiskie --verbose`

- Mostra aiuto:

`udiskie --help`

- Mostra versione:

`udiskie --version`
