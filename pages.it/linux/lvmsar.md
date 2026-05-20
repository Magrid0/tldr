# lvmsar

> Reporter di attività di sistema LVM.
> Non supportato in LVM2; preferire `dmstats`.
> Maggiori informazioni: <https://manned.org/lvmsar>.

- Esegue il reporter legacy (solo sistemi LVM1):

`lvmsar`

- Segnala le statistiche I/O per un dispositivo usando le statistiche device-mapper:

`dmstats report {{/dev/mapper/device}}`

- Elenca le regioni di statistiche per un dispositivo:

`dmstats list {{/dev/mapper/device}}`
