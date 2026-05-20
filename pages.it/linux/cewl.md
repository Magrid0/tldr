# cewl

> Strumento di spidering URL per creare wordlist da contenuti web.
> Maggiori informazioni: <https://digi.ninja/projects/cewl.php#usage>.

- Crea un file wordlist dall'URL dato con profondità massima di 2 collegamenti:

`cewl {{[-d|--depth]}} 2 {{[-w|--write]}} {{path/to/wordlist.txt}} {{url}}`

- Restituisce una wordlist alfanumerica dall'URL dato con parole di almeno 5 caratteri:

`cewl --with-numbers {{[-m|--min_word_length]}} 5 {{url}}`

- Restituisce una wordlist dall'URL dato in modalità debug includendo gli indirizzi email:

`cewl --debug {{[-e|--email]}} {{url}}`

- Restituisce una wordlist dall'URL dato utilizzando l'autenticazione HTTP Basic o Digest:

`cewl --auth_type {{basic|digest}} --auth_user {{username}} --auth_pass {{password}} {{url}}`

- Restituisce una wordlist dall'URL dato tramite un proxy:

`cewl --proxy_host {{host}} --proxy_port {{port}} {{url}}`
