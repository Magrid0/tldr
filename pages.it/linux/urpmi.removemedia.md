# urpmi.removemedia

> Rimuovi media in Mageia.
> Nota: La documentazione di Mageia usa medium e repository come sinonimi.
> Vedi anche: `urpmi`, `urpme`, `urpmi.addmedia`, `urpmi.update`, `urpmf`, `urpmq`.
> Maggiori informazioni: <https://man.linuxreviews.org/man8/urpmi.removemedia.8.html>.

- Rimuovi un medium:

`sudo urpmi.removemedia {{medium}}`

- Rimuovi [t]utti i media:

`sudo urpmi.removemedia -a`

- Rimuovi media corrispondenti in modo [a]pprossimativo ai nomi dei media:

`sudo urpmi.removemedia -y {{parola_chiave}}`
