# phpenmod

> Abilita le estensioni PHP su sistemi basati su Debian.
> Maggiori informazioni: <https://salsa.debian.org/php-team/php-defaults>.

- Abilita l'estensione JSON per ogni SAPI di ogni versione PHP:

`sudo phpenmod {{json}}`

- Abilita l'estensione JSON per PHP 7.3 con SAPI cli:

`sudo phpenmod -v {{7.3}} -s {{cli}} {{json}}`
