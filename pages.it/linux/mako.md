# mako

> Demone di notifiche per compositor Wayland.
> Può essere controllato con `makoctl`.
> Maggiori informazioni: <https://manned.org/mako>.

- Avvia il demone di notifiche `mako`:

`mako`

- Avvia con un file di configurazione personalizzato:

`mako {{[-c|--config]}} {{path/to/config}}`

- Imposta il numero massimo di notifiche visibili:

`mako --max-visible {{5}}`

- Imposta il timeout predefinito in millisecondi (0 per disabilitare):

`mako --default-timeout {{2000}}`

- Raggruppa le notifiche per nome dell'applicazione:

`mako --group-by {{app_name}}`

- Mostra aiuto:

`mako {{[-h|--help]}}`
