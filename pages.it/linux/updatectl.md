# updatectl

> Utility di aggiornamento del sistema.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/updatectl.html>.

- Verifica se il sistema ha aggiornamenti disponibili:

`updatectl check`

- Aggiorna all'ultima versione:

`updatectl update`

- Mostra i target di aggiornamento:

`updatectl`

- Mostra i dati su un target e le sue versioni:

`updatectl list {{target}}`

- Restituisce i dati locali su un target senza recuperarli dalla rete:

`updatectl --offline list {{target}}`

- Applica un aggiornamento a un target e poi riavvia il sistema:

`updatectl --reboot update {{target}}`

- Pulisci le versioni vecchie di un target specificato:

`updatectl vacuum {{target}}`

- Mostra aiuto:

`updatectl {{[-h|--help]}}`
