# dbus-daemon

> Il demone D-Bus, che permette a più programmi di scambiarsi messaggi.
> Maggiori informazioni: <https://dbus.freedesktop.org/doc/dbus-daemon.1.html>.

- Esegue il demone con un file di configurazione:

`dbus-daemon --config-file {{path/to/file}}`

- Esegue il demone con la configurazione standard del bus di messaggi per sessione di login:

`dbus-daemon --session`

- Esegue il demone con la configurazione standard del bus di messaggi di sistema:

`dbus-daemon --system`

- Imposta l'indirizzo su cui ascoltare e ignora il valore di configurazione corrispondente:

`dbus-daemon --address {{address}}`

- Restituisce il PID del processo su `stdout`:

`dbus-daemon --print-pid`

- Forza il bus di messaggi a scrivere nel log di sistema per i messaggi:

`dbus-daemon --syslog`
