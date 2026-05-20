# kmscon

> Usa il framebuffer invece della modalità testo per disegnare un terminale in una TTY.
> Maggiori informazioni: <https://manned.org/kmscon>.

- Avvia `kmscon` sulla prima TTY disponibile:

`sudo kmscon`

- Avvia `kmscon` in una TTY specifica:

`sudo kmscon --vt {{/dev/ttyX|ttyX|X}}`

- Abilita il supporto del mouse:

`sudo kmscon --mouse`

- Specifica il comando da usare per il login:

`sudo kmscon {{[-l|--login]}} {{command}}`

- Avvia sempre `kmscon` in un terminale specifico:

`systemctl enable --now kmsconvt@{{ttyX}}`
