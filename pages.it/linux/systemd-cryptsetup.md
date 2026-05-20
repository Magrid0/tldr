# systemd-cryptsetup

> Crea o rimuove i mapping decrittografati di volumi crittografati. Equivalente di `cryptsetup open` e `cryptsetup close`.
> Gli argomenti per questo comando sono scritti esattamente come una riga in `/etc/crypttab`. Viene utilizzato da systemd per sbloccare i dispositivi all'avvio.
> Vedi anche: `cryptsetup`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-cryptsetup.html>.

- Apre un volume LUKS e crea un mapping decrittografato su `/dev/mapper/nome_mapping`:

`systemd-cryptsetup attach {{nome_mapping}} {{/dev/sdXY}}`

- Apre un volume LUKS con opzioni aggiuntive e crea un mapping decrittografato su `/dev/mapper/nome_mapping`:

`systemd-cryptsetup attach {{nome_mapping}} {{/dev/sdXY}} none {{opzioni_crypttab}}`

- Apre un volume LUKS con un file di chiave e crea un mapping decrittografato su `/dev/mapper/nome_mapping`:

`systemd-cryptsetup attach {{nome_mapping}} {{/dev/sdXY}} {{percorso/del/file_di_chiave}} {{opzioni_crypttab}}`

- Rimuove un mapping esistente:

`systemd-cryptsetup detach {{nome_mapping}}`
