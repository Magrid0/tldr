# systemd-detect-virt

> Rileva l'esecuzione in un ambiente virtualizzato.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-detect-virt.html>.

- Elenca le tecnologie di virtualizzazione rilevabili:

`systemd-detect-virt --list`

- Rileva la virtualizzazione, stampa il risultato e restituisce un codice di stato zero quando è in esecuzione in una VM o un contenitore, e un codice diverso da zero altrimenti:

`systemd-detect-virt`

- Controlla silenziosamente senza stampare nulla:

`systemd-detect-virt {{[-q|--quiet]}}`

- Rileva solo la virtualizzazione dei contenitori:

`systemd-detect-virt {{[-c|--container]}}`

- Rileva solo la virtualizzazione hardware:

`systemd-detect-virt {{[-v|--vm]}}`

- Rileva se è in un ambiente `chroot`:

`systemd-detect-virt {{[-r|--chroot]}}`
