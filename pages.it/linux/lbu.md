# lbu

> Gestisce i file overlay di `apk` su un sistema Alpine Linux senza disco.
> Nota: Sottocomandi come `include` scrivono in `/etc`, che è archiviato in RAM. È necessario eseguire `lbu commit` per salvare le modifiche.
> Maggiori informazioni: <https://wiki.alpinelinux.org/wiki/Alpine_local_backup>.

- Salva le modifiche in memoria persistente (solo i file in `/etc` per impostazione predefinita):

`lbu {{[ci|commit]}}`

- Elenca i file che verrebbero salvati usando `commit`:

`lbu {{[st|status]}}`

- Mostra le modifiche nei file tracciati che verrebbero salvate usando `commit`:

`lbu diff`

- Include un file o directory specifico nell'overlay `apk`:

`lbu {{[inc|include]}} {{path/to/file_or_directory}}`

- Esclude un file o directory specifico in `/etc` dall'overlay `apk`:

`lbu {{[ex|exclude]}} {{path/to/file_or_directory}}`

- Mostra l'elenco dei file inclusi/esclusi manualmente:

`lbu {{include|exclude}} -l`

- Elenca i backup (overlay creati in precedenza):

`lbu {{[lb|list-backup]}}`

- Ripristina un backup overlay:

`lbu revert {{overlay_filename.tar.gz}}`
