# fscrypt

> Strumento Go per gestire la crittografia dei filesystem Linux.
> Maggiori informazioni: <https://github.com/google/fscrypt#example-usage>.

- Prepara il filesystem di root per l'uso con `fscrypt`:

`sudo fscrypt setup`

- Prepara un punto di mount specifico per l'uso con `fscrypt`:

`fscrypt setup {{path/to/directory}}`

- Abilita la crittografia del filesystem per una directory:

`fscrypt encrypt {{path/to/directory}}`

- Sblocca una directory crittografata:

`fscrypt unlock {{path/to/encrypted_directory}}`

- Blocca una directory crittografata:

`fscrypt lock {{path/to/encrypted_directory}}`
