# phpdismod

> Disabilita le estensioni PHP su sistemi basati su Debian.
> Maggiori informazioni: <https://salsa.debian.org/php-team/php-defaults>.

- Disabilita l'estensione JSON per ogni SAPI di ogni versione PHP:

`sudo phpdismod {{json}}`

- Disabilita l'estensione JSON per PHP 7.3 con SAPI cli:

`sudo phpdismod -v {{7.3}} -s {{cli}} {{json}}`
