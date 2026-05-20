# swaks

> Swiss Army Knife SMTP, il tester di transazioni SMTP multiuso.
> Maggiori informazioni: <https://github.com/jetmore/swaks/blob/develop/doc/base.pod>.

- Consegna un'email di test standard a `user@example.com` sulla porta 25 di `test-server.example.net`:

`swaks {{[-t|--to]}} {{user@example.com}} {{[-s|--server]}} {{test-server.example.net}}`

- Consegna un'email di test standard, richiedendo autenticazione CRAM-MD5 come utente `me@example.com`. Un'intestazione "X-Test" verrà aggiunta al corpo dell'email:

`swaks {{[-t|--to]}} {{user@example.com}} {{[-f|--from]}} {{me@example.com}} {{[-a|--auth]}} {{CRAM-MD5}} {{[-au|--auth-user]}} {{me@example.com}} --header-X-Test "{{email_di_test}}"`

- Testa uno scanner antivirus usando EICAR in un allegato. Non mostra la parte DATA del messaggio:

`swaks {{[-t|--to]}} {{user@example.com}} --attach - {{[-s|--server]}} {{test-server.example.com}} {{[-n|--suppress-data]}} {{percorso/del/eicar.txt}}`

- Testa uno scanner antispam usando GTUBE nel corpo di un'email, instradato tramite i record MX per `example.com`:

`swaks {{[-t|--to]}} {{user@example.com}} --body {{percorso/del/file_gtube}}`

- Consegna un'email di test standard a `user@example.com` usando il protocollo LMTP tramite un socket UNIX domain:

`swaks {{[-t|--to]}} {{user@example.com}} --socket {{/var/lda.sock}} --protocol {{LMTP}}`
