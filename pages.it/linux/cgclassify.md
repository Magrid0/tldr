# cgclassify

> Sposta i processi in esecuzione nei `cgroups`.
> Maggiori informazioni: <https://manned.org/cgclassify>.

- Sposta il processo con un PID specifico nel [g]ruppo di controllo student nella gerarchia CPU:

`cgclassify -g {{cpu:student}} {{1234}}`

- Sposta il processo con un PID specifico nei gruppi di controllo basati sul file di configurazione `/etc/cgrules.conf`:

`cgclassify {{1234}}`

- Sposta il processo con un PID specifico nel [g]ruppo di controllo student nella gerarchia CPU. Nota: Il demone del servizio `cgred` non modifica i `cgroups` del PID specifico e dei suoi figli (basato su `/etc/cgrules.conf`):

`cgclassify --sticky -g {{cpu:/student}} {{1234}}`
