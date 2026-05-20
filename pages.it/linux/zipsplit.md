# zipsplit

> Divide un archivio Zip in archivi Zip più piccoli.
> Maggiori informazioni: <https://manned.org/zipsplit>.

- Dividi l'archivio Zip in parti non più grandi di 36000 byte (36 MB):

`zipsplit {{path/to/archive.zip}}`

- Usa un dato numero di byte come limite della parte:

`zipsplit -n {{dimensione}} {{path/to/archive.zip}}`

- Metti in [p]ausa tra la creazione di ogni parte:

`zipsplit -p -n {{dimensione}} {{path/to/archive.zip}}`

- Output degli archivi Zip più piccoli in una directory specificata:

`zipsplit -b {{path/to/directory_output}} -n {{dimensione}} {{path/to/archive.zip}}`
