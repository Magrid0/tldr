# spectre-meltdown-checker

> Strumento di rilevamento delle mitigazioni per Spectre e Meltdown.
> Maggiori informazioni: <https://manned.org/spectre-meltdown-checker>.

- Controlla il kernel in esecuzione per Spectre o Meltdown:

`sudo spectre-meltdown-checker`

- Controlla il kernel in esecuzione e mostra una spiegazione delle azioni da intraprendere per mitigare una vulnerabilità:

`sudo spectre-meltdown-checker --explain`

- Controlla varianti specifiche (predefinito: tutte):

`sudo spectre-meltdown-checker --variant {{1|2|3|3a|4|l1tf|msbds|mfbds|mlpds|mdsum|taa|mcespc|srbds}}`

- Mostra l'output usando un formato di output specifico:

`sudo spectre-meltdown-checker --batch {{text|json|nrpe|prometheus|short}}`

- Non usa l'interfaccia `/sys` anche se presente:

`sudo spectre-meltdown-checker --no-sysfs`

- Controlla un kernel non in esecuzione:

`sudo spectre-meltdown-checker --kernel {{percorso/del/file_kernel}}`
