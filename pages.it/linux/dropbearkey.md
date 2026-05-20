# dropbearkey

> Genera chiavi SSH in formato Dropbear.
> Maggiori informazioni: <https://manned.org/dropbearkey>.

- Genera una chiave SSH di [t]ipo ed25519 e la scrive nel [f]ile di chiave:

`dropbearkey -t {{ed25519}} -f {{path/to/key_file}}`

- Genera una chiave SSH di [t]ipo ecdsa e la scrive nel [f]ile di chiave:

`dropbearkey -t {{ecdsa}} -f {{path/to/key_file}}`

- Genera una chiave SSH di [t]ipo RSA con [s]ize di 4096 bit e la scrive nel [f]ile di chiave:

`dropbearkey -t {{rsa}} -s {{4096}} -f {{path/to/key_file}}`

- Stampa l'impronta della chiave privata e la chiave pubblica nel [f]ile di chiave:

`dropbearkey -y -f {{path/to/key_file}}`
