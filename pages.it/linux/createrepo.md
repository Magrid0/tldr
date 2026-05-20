# createrepo

> Inizializza un repository RPM in una directory, inclusi tutti i file XML e SQLite.
> Maggiori informazioni: <https://manned.org/createrepo>.

- Inizializza un repository di base in una directory:

`createrepo {{path/to/directory}}`

- Inizializza un repository, esclude i RPM di test e mostra log dettagliati:

`createrepo {{[-v|--verbose]}} {{[-x|--excludes]}} {{test_*.rpm}} {{path/to/directory}}`

- Inizializza un repository, utilizzando SHA1 come algoritmo di checksum e ignorando i collegamenti simbolici:

`createrepo {{[-S|--skip-symlinks]}} {{[-s|--checksum]}} {{sha1}} {{path/to/directory}}`
