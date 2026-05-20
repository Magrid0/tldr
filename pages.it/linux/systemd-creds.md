# systemd-creds

> Elenca, mostra, crittografa e decrittografa le credenziali dei servizi.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-creds.html>.

- Crittografa un file e imposta un nome specifico:

`systemd-creds encrypt --name {{nome}} {{percorso/del/file_input}} {{percorso/del/file_output}}`

- Decrittografa il file di nuovo:

`systemd-creds decrypt {{percorso/del/file_input}} {{percorso/del/file_output}}`

- Crittografa il testo da `stdin`:

`echo -n {{testo}} | systemd-creds encrypt --name {{nome}} - {{percorso/del/file_output}}`

- Crittografa il testo e lo aggiunge al file `.service` (le credenziali saranno disponibili in `$CREDENTIALS_DIRECTORY`):

`echo -n {{testo}} | systemd-creds encrypt --name {{nome}} --pretty - - >> {{servizio}}`

- Crea una credenziale valida solo fino al timestamp indicato:

`systemd-creds encrypt --not-after "{{timestamp}}" {{percorso/del/file_input}} {{percorso/del/file_output}}`
