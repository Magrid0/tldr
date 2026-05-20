# dirb

> Analizza server web HTTP in cerca di directory e file.
> Maggiori informazioni: <https://manned.org/dirb>.

- Analizza un server web usando la wordlist predefinita:

`dirb {{https://example.org}}`

- Analizza un server web usando una wordlist personalizzata:

`dirb {{https://example.org}} {{path/to/wordlist.txt}}`

- Analizza un server web in modo non ricorsivo:

`dirb {{https://example.org}} -r`

- Analizza un server web usando un user-agent e un cookie specificati per richieste HTTP:

`dirb {{https://example.org}} -a {{user_agent_string}} -c {{cookie_string}}`
