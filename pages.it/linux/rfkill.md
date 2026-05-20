# rfkill

> Abilita e disabilita dispositivi wireless.
> Maggiori informazioni: <https://manned.org/rfkill>.

- Elenca i dispositivi:

`rfkill`

- Filtra per colonne:

`rfkill {{[-o|--output]}} {{ID,TYPE,DEVICE,...}}`

- Blocca i dispositivi per tipo:

`rfkill block {{bluetooth|wifi|gps|nfc|...}}`

- Sblocca i dispositivi per tipo:

`rfkill unblock {{bluetooth|wifi|gps|nfc|...}}`

- Output in formato JSON:

`rfkill {{[-J|--json]}}`
