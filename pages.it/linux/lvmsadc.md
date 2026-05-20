# lvmsadc

> Collettore di dati di attività di sistema LVM (non supportato in LVM2; preferire `dmstats`).
> Maggiori informazioni: <https://manned.org/lvmsadc>.

- Esegue il collettore (solo sistemi LVM1 legacy):

`lvmsadc`

- Segnala le statistiche I/O usando il sostituto device-mapper:

`dmstats report {{/dev/mapper/device}}`
