# phar

> Crea, aggiorna o estrae archivi PHP (PHAR).
> Maggiori informazioni: <https://manned.org/phar>.

- Aggiunge uno o più file o directory a un file Phar:

`phar add -f {{percorso/del/file_phar}} {{percorso/del/file_o_directory1 percorso/del/file_o_directory2 ...}}`

- Mostra i contenuti di un file Phar:

`phar list -f {{percorso/del/file_phar}}`

- Elimina il file o directory specificato da un file Phar:

`phar delete -f {{percorso/del/file_phar}} -e {{file_o_directory}}`

- Comprime o decomprime file e directory in un file Phar:

`phar compress -f {{percorso/del/file_phar}} -c {{algoritmo}}`

- Ottiene informazioni su un file Phar:

`phar info -f {{percorso/del/file_phar}}`

- Firma un file Phar con un algoritmo di hash specifico:

`phar sign -f {{percorso/del/file_phar}} -h {{algoritmo}}`

- Firma un file Phar con una chiave privata OpenSSL:

`phar sign -f {{percorso/del/file_phar}} -h openssl -y {{percorso/chiave_privata}}`

- Mostra aiuto e gli algoritmi di hash/compressione disponibili:

`phar help`
