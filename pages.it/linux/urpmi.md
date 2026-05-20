# urpmi

> Installa pacchetti in Mageia.
> Vedi anche: `urpmi.update`, `urpme`, `urpmi.addmedia`, `urpmi.removemedia`, `urpmf`, `urpmq`.
> Maggiori informazioni: <https://man.linuxreviews.org/man8/urpmi.8.html>.

- Installa un pacchetto dal repository o da un file RPM locale:

`sudo urpmi {{pacchetto|percorso/del/file.rpm}}`

- Scarica un pacchetto senza installarlo:

`urpmi --no-install {{pacchetto}}`

- Aggiorna tutti i pacchetti installati (esegui `urpmi.update -a` per ottenere gli aggiornamenti disponibili):

`sudo urpmi --auto-select`

- Aggiorna un pacchetto su una o più macchine nella rete secondo `/etc/urpmi/parallel.cfg`:

`sudo urpmi --parallel local {{pacchetto}}`

- Marca tutti i pacchetti orfani come installati manualmente:

`sudo urpmi $(urpmq --auto-orphans -f)`
