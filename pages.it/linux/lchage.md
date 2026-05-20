# lchage

> Mostra o modifica i criteri di scadenza della password utente.
> Maggiori informazioni: <https://manned.org/lchage>.

- Disabilita la scadenza della password per l'utente:

`sudo lchage --date -1 {{username}}`

- Mostra i criteri di scadenza della password per l'utente:

`sudo lchage --list {{username}}`

- Richiede il cambio password per l'utente un certo numero di giorni dopo l'ultimo cambio password:

`sudo lchage --maxdays {{number_of_days}} {{username}}`

- Inizia ad avvisare l'utente un certo numero di giorni prima della scadenza della password:

`sudo lchage --warndays {{number_of_days}} {{username}}`
