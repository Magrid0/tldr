# systemd-inhibit

> Impedisce al sistema di entrare in determinati stati di alimentazione.
> I blocchi inibitori possono essere utilizzati per bloccare o ritardare le richieste di sospensione e spegnimento del sistema, nonché la gestione automatica dell'inattività.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-inhibit.html>.

- Elenca tutti i blocchi inibitori attivi e i motivi della loro creazione:

`systemd-inhibit`

- Blocca lo spegnimento del sistema per un numero specificato di secondi con il comando `sleep`:

`systemd-inhibit --what shutdown sleep {{5}}`

- Impedisce al sistema di sospendersi o entrare in inattività fino al completamento del download:

`systemd-inhibit --what sleep:idle wget {{https://example.com/file}}`

- Ignora l'interruttore di chiusura del coperchio fino all'uscita dello script:

`systemd-inhibit --what sleep:handle-lid-switch {{percorso/dello/script}}`

- Ignora la pressione del pulsante di accensione mentre il comando è in esecuzione:

`systemd-inhibit --what handle-power-key {{comando}}`

- Descrive chi e perché ha creato l'inibitore (predefinito: il comando e i suoi argomenti per `--who` e `Unknown reason` per `--why`):

`systemd-inhibit --who {{$USER}} --why {{motivo}} --what {{operazione}} {{comando}}`
