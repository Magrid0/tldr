# losetup

> Configura e controlla i dispositivi ad anello.
> Maggiori informazioni: <https://manned.org/losetup>.

- Elenca i dispositivi ad anello con informazioni dettagliate:

`losetup {{[-a|--all]}}`

- Collega un file a un dato dispositivo ad anello:

`sudo losetup {{/dev/loop}} /{{path/to/file}}`

- Collega un file a un nuovo dispositivo ad anello libero e scansiona il dispositivo per le partizioni:

`sudo losetup --show {{[-P|--partscan]}} {{[-f|--find]}} /{{path/to/file}}`

- Collega un file a un dispositivo ad anello in sola lettura:

`sudo losetup {{[-r|--read-only]}} {{/dev/loop}} /{{path/to/file}}`

- Scollega tutti i dispositivi ad anello:

`sudo losetup {{[-D|--detach-all]}}`

- Scollega un dato dispositivo ad anello:

`sudo losetup {{[-d|--detach]}} {{/dev/loop}}`
