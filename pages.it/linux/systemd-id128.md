# systemd-id128

> Genera e stampa identificatori sd-128.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-id128.html>.

- Genera un nuovo identificatore casuale:

`systemd-id128 new`

- Stampa l'identificatore della macchina corrente:

`systemd-id128 machine-id`

- Stampa l'identificatore dell'avvio corrente:

`systemd-id128 boot-id`

- Stampa l'identificatore dell'invocazione del servizio corrente (disponibile nei servizi systemd):

`systemd-id128 invocation-id`

- Genera un nuovo identificatore casuale e lo stampa come UUID (cinque gruppi di cifre separate da trattini):

`systemd-id128 new {{[-u|--uuid]}}`
