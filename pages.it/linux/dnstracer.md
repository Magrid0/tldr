# dnstracer

> Il comando dnstracer determina da dove un DNS ottiene le sue informazioni.
> Maggiori informazioni: <https://manned.org/dnstracer>.

- Scopri da dove il tuo DNS locale ha ottenuto le informazioni su www.example.com:

`dnstracer {{www.example.com}}`

- Avvia con un DNS [s]pecifico che già conosci:

`dnstracer -s {{dns.example.org}} {{www.example.com}}`

- Interroga solo server IPv[4]:

`dnstracer -4 {{www.example.com}}`

- [r]iprova ogni richiesta 5 volte in caso di fallimento:

`dnstracer -r {{5}} {{www.example.com}}`

- Mostra tutti i passaggi durante l'esecuzione:

`dnstracer -v {{www.example.com}}`

- Mostra una [p]anoramica di tutte le risposte ricevute dopo l'esecuzione:

`dnstracer -o {{www.example.com}}`
