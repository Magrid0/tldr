# agetty

> `getty` alternativa: apre una porta `tty`, richiede un nome di login e richiama il comando `/bin/login`.
> Normalmente viene richiamato da `init`.
> Nota: il baud rate è la velocità di trasferimento dati tra un terminale e un dispositivo tramite una connessione seriale.
> Maggiori informazioni: <https://manned.org/agetty>.

- Collega `stdin` a una porta (relativa a `/dev`) e opzionalmente specifica un baud rate (predefinito a 9600):

`agetty {{tty}} {{115200}}`

- Presuppone che `stdin` sia già collegato a un `tty` e imposta un timeout per il login:

`agetty {{[-t|--timeout]}} {{timeout_in_secondi}} -`

- Presuppone che il `tty` sia a 8 bit, sovrascrivendo la variabile d'ambiente `$TERM` impostata da `init`:

`agetty {{[-8|--8bits]}} - {{term_var}}`

- Salta il login (nessun login) e richiama, come root, un altro programma di login invece di `/bin/login`:

`agetty {{[-n|--skip-login]}} {{[-l|--login-program]}} {{programma_login}} {{tty}}`

- Non mostra il file pre-login (issue) (`/etc/issue` in modo predefinito) prima di scrivere il prompt di login:

`agetty {{[-i|--noissue]}} -`

- Cambia la directory root e scrive un host fittizio specifico nel file `utmp`:

`agetty {{[-r|--chroot]}} /{{path/to/root_directory}} {{[-H|--host]}} {{host_fittizio}} -`
