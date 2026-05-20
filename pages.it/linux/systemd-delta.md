# systemd-delta

> Trova i file di configurazione systemd sovrascritti.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-delta.html>.

- Mostra tutti i file di configurazione sovrascritti:

`systemd-delta`

- Mostra solo file di tipi specifici (elenco separato da virgole):

`systemd-delta {{[-t|--type]}} {{masked|equivalent|redirected|overridden|extended|unchanged}}`

- Mostra solo file il cui percorso inizia con il prefisso specificato (Nota: un prefisso è una directory contenente sottodirectory con file di configurazione systemd):

`systemd-delta {{/etc|/run|/usr/lib|...}}`

- Limita ulteriormente il percorso di ricerca aggiungendo un suffisso (il prefisso è opzionale):

`systemd-delta {{prefisso}}/{{tmpfiles.d|sysctl.d|systemd/system|...}}`
