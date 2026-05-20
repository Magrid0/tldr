# phpquery

> Gestore di estensioni PHP per sistemi basati su Debian.
> Maggiori informazioni: <https://code.google.com/archive/p/phpquery/wikis/CommandLineInterface.wiki>.

- Elenca le versioni PHP disponibili:

`sudo phpquery -V`

- Elenca le SAPI disponibili per PHP 7.3:

`sudo phpquery -v {{7.3}} -S`

- Elenca le estensioni abilitate per PHP 7.3 con SAPI cli:

`sudo phpquery -v {{7.3}} -s {{cli}} -M`

- Controlla se l'estensione JSON è abilitata per PHP 7.3 con SAPI apache2:

`sudo phpquery -v {{7.3}} -s {{apache2}} -m {{json}}`
