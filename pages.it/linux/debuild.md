# debuild

> Costruisce un pacchetto Debian dal sorgente.
> Maggiori informazioni: <https://manned.org/debuild>.

- Costruisce il pacchetto nella directory corrente:

`debuild`

- Costruisce solo un pacchetto binario:

`debuild -b`

- Non esegue lintian dopo la costruzione del pacchetto:

`debuild --no-lintian`
