# postconf

> Utilità di configurazione di Postfix.
> Questo comando mostra i valori dei parametri di configurazione di `main.cf` per impostazione predefinita e avvisa di possibili nomi di parametri errati. Può anche modificare i valori dei parametri di configurazione di `main.cf`.
> Maggiori informazioni: <https://manned.org/postconf>.

- Specifica la directory del file di configurazione `main.cf` invece della directory di configurazione predefinita:

`postconf -c {{percorso/della/directory_configurazione}}`

- Modifica il file di configurazione `main.cf` e aggiorna le impostazioni dei parametri con le coppie "nome=valore":

`postconf -e`

- Mostra le impostazioni predefinite dei parametri di `main.cf` invece delle impostazioni attuali:

`postconf -d`

- Mostra i parametri solo della classe specificata:

`postconf -C {{builtin|service|user|all}}`

- Elenca i tipi di plug-in SASL disponibili per il server SMTP Postfix. Il tipo di plug-in viene selezionato con il parametro di configurazione `smtpd_sasl_type` specificando `cyrus` o `dovecot` come nome:

`postconf -a`

- Elenca i nomi di tutti i tipi di tabelle di ricerca supportate. Le tabelle di ricerca sono specificate come `type:name` nei file di configurazione dove il tipo può essere `btree`, `cdb`, `hash`, `mysql`, ecc.:

`postconf -m`
