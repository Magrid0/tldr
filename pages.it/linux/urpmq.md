# urpmq

> Interroga informazioni su pacchetti e media in Mageia.
> Vedi anche: `urpmi`, `urpmi.update`, `urpmi.addmedia`, `urpmi.removemedia`, `urpmf`, `urpme`.
> Maggiori informazioni: <https://man.linuxreviews.org/man8/urpmq.8.html>.

- Mostra informazioni su un pacchetto installabile:

`urpmq -i {{pacchetto}}`

- Mostra le dipendenze dirette di un pacchetto:

`urpmq --requires {{pacchetto}}`

- Mostra le dipendenze dirette e indirette di un pacchetto:

`urpmq {{[-d|--requires-recursive]}} {{pacchetto}}`

- Elenca i pacchetti non installati necessari per un file RPM con le loro fonti:

`sudo urpmq {{[-d|--requires-recursive]}} -m --sources {{percorso/del/file.rpm}}`

- Elenca tutti i media configurati con i loro URL, inclusi i media inattivi:

`urpmq --list-media --list-url`

- Cerca un pacchetto stampando [g]ruppo, versione e [r]ilascio:

`urpmq -g -r {{[-y|--fuzzy]}} {{parola_chiave}}`

- Cerca un pacchetto usando il suo nome esatto:

`urpmq -g -r {{pacchetto}}`
