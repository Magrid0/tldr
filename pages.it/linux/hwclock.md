# hwclock

> Legge o modifica l'orologio hardware.
> Maggiori informazioni: <https://manned.org/hwclock>.

- Mostra l'ora corrente riportata dall'orologio hardware:

`sudo hwclock`

- Scrive l'ora corrente dell'orologio software nell'orologio hardware (a volte usato durante la configurazione del sistema):

`sudo hwclock {{[-w|--systohc]}}`

- Scrive l'ora corrente dell'orologio hardware nell'orologio software:

`sudo hwclock {{[-s|--hctosys]}}`
