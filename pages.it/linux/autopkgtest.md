# autopkgtest

> Esegue test sui pacchetti Debian.
> Maggiori informazioni: <https://manned.org/autopkgtest>.

- Costruisce il pacchetto nella directory corrente e esegue tutti i test direttamente sul sistema:

`autopkgtest -- {{null}}`

- Esegue un test specifico per il pacchetto nella directory corrente:

`autopkgtest --test-name={{nome_test}} -- {{null}}`

- Scarica e costruisce un pacchetto specifico con `apt-get`, poi esegue tutti i test:

`autopkgtest {{pacchetto}} -- {{null}}`

- Testa il pacchetto nella directory corrente utilizzando una nuova directory root:

`autopkgtest -- {{chroot}} {{path/to/nuova_root}}`

- Testa il pacchetto nella directory corrente senza ricostruirlo:

`autopkgtest {{[-B|--no-built-binaries]}} -- {{null}}`
