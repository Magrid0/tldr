# userdbctl

> Ispeziona utenti, gruppi e appartenenze a gruppi sul sistema.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/userdbctl.html>.

- Elenca tutti i record utente conosciuti:

`userdbctl`

- Mostra i dettagli di un utente specifico:

`userdbctl user {{nome_utente}}`

- Elenca tutti i gruppi conosciuti:

`userdbctl group`

- Mostra i dettagli di un gruppo specifico:

`userdbctl group {{nome_gruppo}}`

- Elenca tutti i servizi che forniscono definizioni di utenti/gruppi al sistema:

`userdbctl services`
