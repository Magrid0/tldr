# rc-status

> Mostra informazioni sullo stato dei runlevel.
> Vedi anche: `openrc`.
> Maggiori informazioni: <https://manned.org/rc-status>.

- Mostra un riepilogo dei servizi e del loro stato:

`rc-status`

- Include i servizi di tutti i runlevel nel riepilogo:

`rc-status {{[-a|--all]}}`

- Elenca i servizi che sono crashati:

`rc-status {{[-c|--crashed]}}`

- Elenca i servizi avviati manualmente:

`rc-status {{[-m|--manual]}}`

- Elenca i servizi supervisionati:

`rc-status {{[-S|--supervised]}}`

- Mostra il runlevel corrente:

`rc-status {{[-r|--runlevel]}}`

- Elenca tutti i runlevel:

`rc-status {{[-l|--list]}}`
