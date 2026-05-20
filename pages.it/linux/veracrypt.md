# veracrypt

> Software di crittografia del disco gratuito e open source.
> Maggiori informazioni: <https://arcanecode.com/2021/06/21/veracrypt-on-the-command-line-for-ubuntu-linux/>.

- Crea un nuovo volume tramite un'interfaccia utente testuale e usa `/dev/urandom` come fonte di dati casuali:

`veracrypt {{[-t|--text]}} {{[-c|--create]}} --random-source={{/dev/urandom}}`

- Decifra un volume interattivamente tramite un'interfaccia utente testuale e montalo in una directory:

`veracrypt {{[-t|--text]}} {{percorso/del/volume}} {{percorso/del/punto_di_montaggio}}`

- Decifra una partizione usando un keyfile e montala in una directory:

`veracrypt {{[-k|--keyfiles]}} {{percorso/del/keyfile}} {{/dev/sdXN}} {{percorso/del/punto_di_montaggio}}`

- Smonta un volume nella directory in cui è montato:

`veracrypt {{[-d|--dismount]}} {{percorso/del/punto_montato}}`
