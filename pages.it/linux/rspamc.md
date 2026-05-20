# rspamc

> Client per server `rspamd`.
> Maggiori informazioni: <https://manned.org/rspamc>.

- Addestra il filtro bayesiano a riconoscere un'email come spam:

`rspamc learn_spam {{path/to/email_file}}`

- Addestra il filtro bayesiano a riconoscere un'email come ham:

`rspamc learn_ham {{path/to/email_file}}`

- Genera un rapporto manuale su un'email:

`rspamc symbols {{path/to/email_file}}`

- Mostra le statistiche del server:

`rspamc stat`
