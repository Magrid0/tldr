# raw

> Collega un dispositivo a caratteri raw Unix.
> Maggiori informazioni: <https://manned.org/raw.8>.

- Collega un dispositivo a caratteri raw a un dispositivo a blocchi:

`raw /dev/raw/raw{{1}} {{/dev/block_device}}`

- Interroga un binding esistente invece di impostarne uno nuovo:

`raw /dev/raw/raw{{1}}`

- Interroga tutti i dispositivi raw collegati:

`raw {{[-qa|--query --all]}}`
