# debsecan

> Analizzatore di sicurezza Debian, uno strumento per elencare le vulnerabilità su una specifica installazione Debian.
> Maggiori informazioni: <https://manned.org/debsecan>.

- Elenca i pacchetti installati vulnerabili sull'host corrente:

`debsecan`

- Elenca i pacchetti installati vulnerabili di una suite specifica:

`debsecan --suite {{release_code_name}}`

- Elenca solo le vulnerabilità risolte:

`debsecan --suite {{release_code_name}} --only-fixed`

- Elenca solo le vulnerabilità risolte di unstable ("sid") e invia per email a root:

`debsecan --suite {{sid}} --only-fixed --format {{report}} --mailto {{root}} --update-history`

- Aggiorna i pacchetti installati vulnerabili:

`sudo apt upgrade $(debsecan --only-fixed --format {{packages}})`
