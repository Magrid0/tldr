# urpmi.update

> Aggiorna la lista dei pacchetti da un repository di pacchetti in Mageia.
> Nota: La documentazione di Mageia usa medium e repository come sinonimi.
> Vedi anche: `urpmi`, `urpme`, `urpmi.addmedia`, `urpmi.removemedia`, `urpmf`, `urpmq`.
> Maggiori informazioni: <https://man.linuxreviews.org/man8/urpmi.update.8.html>.

- Aggiorna tutti i media abilitati:

`urpmi.update -a`

- Aggiorna media specifici (inclusi i media disabilitati):

`urpmi.update {{medium1 medium2 ...}}`

- Aggiorna tutti i media che contengono una parola chiave specifica:

`urpmi.update {{parola_chiave}}`

- Aggiorna tutti i media configurati:

`urpmi.update e`
