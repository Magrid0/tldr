# boltctl

> Controlla i dispositivi Thunderbolt.
> Maggiori informazioni: <https://manned.org/boltctl>.

- Elenca i dispositivi connessi (e autorizzati):

`boltctl`

- Elenca i dispositivi connessi, inclusi quelli non autorizzati:

`boltctl list`

- Autorizza un dispositivo temporaneamente:

`boltctl authorize {{device_uuid}}`

- Autorizza e ricorda un dispositivo:

`boltctl enroll {{device_uuid}}`

- Revoca un dispositivo precedentemente autorizzato:

`boltctl forget {{device_uuid}}`

- Mostra maggiori informazioni su un dispositivo:

`boltctl info {{device_uuid}}`
