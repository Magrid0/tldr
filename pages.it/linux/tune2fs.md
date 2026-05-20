# tune2fs

> Regola i parametri di un filesystem ext2, ext3 o ext4.
> Può essere usato su filesystem montati.
> Maggiori informazioni: <https://manned.org/tune2fs>.

- Imposta il numero massimo di conteggi prima che un filesystem venga controllato a 2:

`sudo tune2fs -c 2 {{/dev/sdXN}}`

- Imposta l'etichetta del filesystem su `MY_LABEL`:

`sudo tune2fs -L 'MY_LABEL' {{/dev/sdXN}}`

- Abilita discard e attributi estesi specificati dall'utente per un filesystem:

`sudo tune2fs -o discard,user_xattr {{/dev/sdXN}}`

- Abilita il journaling per un filesystem:

`sudo tune2fs -o has_journal {{/dev/sdXN}}`

- Assegna un nuovo UUID generato casualmente a un filesystem:

`sudo tune2fs -U random {{/dev/sdXN}}`
