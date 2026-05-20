# getcap

> Mostra il nome e le capacità di ogni file specificato.
> Maggiori informazioni: <https://manned.org/getcap>.

- Ottiene le capacità per i file indicati:

`getcap {{path/to/file1 path/to/file2 ...}}`

- Ottiene le capacità per tutti i file ricorsivamente nelle directory indicate:

`getcap -r {{path/to/directory1 path/to/directory2 ...}}`

- Mostra tutte le voci cercate anche se non sono impostate capacità:

`getcap -v {{path/to/file1 path/to/file2 ...}}`
