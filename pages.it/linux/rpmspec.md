# rpmspec

> Interroga un file spec RPM.
> Maggiori informazioni: <https://manned.org/rpmspec>.

- Elenca i pacchetti binari che verrebbero generati da un file spec RPM:

`rpmspec --query {{path/to/rpm.spec}}`

- Elenca tutte le opzioni per `--queryformat`:

`rpmspec --querytags`

- Ottiene informazioni di riepilogo per singoli pacchetti binari generati da un file spec RPM:

`rpmspec --query --queryformat "{{%{name}: %{summary}\n}}" {{path/to/rpm.spec}}`

- Ottiene il pacchetto sorgente che verrebbe generato da un file spec RPM:

`rpmspec --query --srpm {{path/to/rpm.spec}}`

- Analizza un file spec RPM su `stdout`:

`rpmspec --parse {{path/to/rpm.spec}}`
