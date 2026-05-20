# mokutil

> Configura le chiavi del proprietario della macchina (MOK) per Secure Boot.
> Alcune operazioni, come abilitare e disabilitare Secure Boot o registrare chiavi, richiedono un riavvio.
> Maggiori informazioni: <https://manned.org/mokutil>.

- Mostra se Secure Boot è abilitato:

`mokutil --sb-state`

- Abilita Secure Boot:

`mokutil --enable-validation`

- Disabilita Secure Boot:

`mokutil --disable-validation`

- Elenca le chiavi registrate:

`mokutil {{[-l|--list-enrolled]}}`

- Registra una nuova chiave:

`mokutil {{[-i|--import]}} {{path/to/key.der}}`

- Elenca le chiavi da registrare:

`mokutil {{[-N|--list-new]}}`

- Imposta la verbosità di shim:

`mokutil --set-verbosity true`
