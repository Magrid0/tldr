# pacreport

> Genera un report dei pacchetti installati.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/pacreport.pod>.

- Genera un riepilogo dei pacchetti installati:

`pacreport`

- Elenca i file non posseduti:

`pacreport --unowned-files`

- Elenca i file dei pacchetti mancanti:

`pacreport --missing-files`

- Cerca file di backup non uniti (es. `.pacnew`, `.pacsave`) in `/etc`:

`pacreport --backups`

- Mostra i pacchetti in un gruppo specifico che non sono attualmente installati:

`pacreport --group {{nome_gruppo}}`
