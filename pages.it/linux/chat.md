# chat

> Automatizza le conversazioni con un modem o un dispositivo seriale.
> Comunemente usato per stabilire connessioni PPP (Point-to-Point Protocol).
> Maggiori informazioni: <https://manned.org/chat>.

- Esegue direttamente uno script chat:

`chat '{{expect_send_pairs}}'`

- Esegue uno script chat da un file:

`chat -f '{{path/to/chat_script}}'`

- Imposta un timeout personalizzato (in secondi) per attendere una risposta:

`chat -t {{timeout_in_seconds}} '{{expect_send_pairs}}'`

- Abilita l'output verboso per registrare la conversazione su `syslog`:

`chat -v '{{expect_send_pairs}}'`

- Utilizza un file di report per registrare stringhe specifiche ricevute durante la conversazione:

`chat -r {{path/to/report_file}} '{{expect_send_pairs}}'`

- Componi un numero di telefono utilizzando una variabile, sostituendo `\T` nello script:

`chat -T '{{phone_number}}' '{{"ATDT\\T CONNECT"}}'`

- Includi una condizione di interruzione se viene ricevuta una stringa specifica:

`chat 'ABORT "{{error_string}}" {{expect_send_pairs}}'`
