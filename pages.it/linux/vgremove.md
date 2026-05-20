# vgremove

> Rimuove volume group in LVM.
> Maggiori informazioni: <https://manned.org/vgremove>.

- Rimuove un volume group con conferma:

`sudo vgremove {{volume_group}}`

- Rimuove forzatamente un volume group senza conferma:

`sudo vgremove {{[-f|--force]}} {{volume_group}}`

- Imposta il livello di debug per la registrazione dettagliata al livello 2 (ripeti `--debug` fino a 6 volte per aumentare il livello):

`sudo vgremove {{[-d|--debug]}} {{[-d|--debug]}} {{volume_group}}`

- Usa una specifica impostazione di configurazione per sovrascrivere i default:

`sudo vgremove --config '{{global/locking_type=1}}' {{volume_group}}`

- Mostra aiuto:

`vgremove {{[-h|--help]}}`
