# bcachefs device

> Gestisce i dispositivi all'interno di un filesystem `bcachefs` in esecuzione.
> Maggiori informazioni: <https://bcachefs-docs.readthedocs.io/en/latest/mgmt-devicemanagement.html>.

- Formatta e aggiunge un nuovo dispositivo a un filesystem esistente:

`sudo bcachefs device add --label {{group}}.{{name}} {{path/to/mountpoint}} {{path/to/device}}`

- Migra i dati da un dispositivo per prepararlo alla rimozione:

`bcachefs device evacuate {{path/to/device}}`

- Rimuove permanentemente un dispositivo da un filesystem:

`bcachefs device remove {{path/to/device}}`
