# grub2-mkpasswd-pbkdf2

> Genera una password hash per GRUB.
> Maggiori informazioni: <https://manned.org/grub2-mkpasswd-pbkdf2>.

- Crea un hash della password per GRUB 2 usando PBKDF2 e lo stampa su `stdout`:

`sudo grub2-mkpasswd-pbkdf2 {{[-c|--iteration-count]}} {{number_of_pbkdf2_iterations}} {{[-s|--salt]}} {{salt_length}}`
