# ndctl

> Utilità per la gestione di DIMM non volatili.
> Maggiori informazioni: <https://manned.org/ndctl>.

- Crea un namespace in modalità `fsdax`:

`ndctl create-namespace --mode={{fsdax}}`

- Cambia la modalità di un namespace a `raw`:

`ndctl create-namespace --reconfigure={{namespaceX.Y}} --mode={{raw}}`

- Verifica la coerenza di un namespace in modalità settore e lo ripara se necessario:

`ndctl check-namespace --repair {{namespaceX.Y}}`

- Elenca tutti i namespace, le regioni e i bus (inclusi quelli disabilitati):

`ndctl list --namespaces --regions --buses --idle`

- Elenca un namespace specifico includendo molte informazioni aggiuntive:

`ndctl list -vvv --namespace={{namespaceX.Y}}`

- Esegue un monitor per osservare eventi di salute SMART per NVDIMM sul bus `ACPI.NFIT`:

`ndctl monitor --bus={{ACPI.NFIT}}`

- Rimuove un namespace (quando possibile) o lo resetta allo stato iniziale:

`ndctl destroy-namespace --force {{namespaceX.Y}}`
