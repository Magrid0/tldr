# urpmi.addmedia

> Aggiungi media in Mageia.
> Nota: La documentazione di Mageia usa medium e repository come sinonimi.
> Vedi anche: `urpmi`, `urpmi.update`, `urpme`, `urpmi.removemedia`, `urpmf`, `urpmq`.
> Maggiori informazioni: <https://man.linuxreviews.org/man8/urpmi.addmedia.8.html>.

- Aggiungi un medium:

`sudo urpmi.addmedia {{medium}} {{ftp://ftp.site.com/path/to/Mageia/RPMS}}`

- Aggiungi un medium da un disco rigido (esegui prima `genhdlist2` nella directory):

`sudo urpmi.addmedia --distrib HD file://{{percorso/della/repo}}`

- Aggiungi media importanti da un mirror scelto:

`sudo urpmi.addmedia --distrib ftp://{{sito_mirror}}/mirror/mageia/distrib/{{versione}}/{{arch}}`

- Seleziona automaticamente i mirror da una lista di mirror:

`sudo urpmi.addmedia --distrib --mirrorlist {{mirrorlist}}`
