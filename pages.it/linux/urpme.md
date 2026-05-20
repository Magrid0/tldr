# urpme

> Disinstalla pacchetti in Mageia.
> Vedi anche: `urpmi`, `urpmi.update`, `urpmi.addmedia`, `urpmi.removemedia`, `urpmf`, `urpmq`.
> Maggiori informazioni: <https://man.linuxreviews.org/man8/urpme.8.html>.

- Disinstalla un pacchetto:

`sudo urpme {{pacchetto}}`

- Disinstalla i pacchetti orfani (Nota: usalo con cautela poiché potrebbe rimuovere involontariamente pacchetti importanti):

`sudo urpme --auto-orphans`

- Disinstalla un pacchetto e le sue dipendenze:

`sudo urpme --auto-orphans {{pacchetto}}`
