# semodule

> Gestisce i moduli delle politiche SELinux.
> Vedi anche: `audit2allow`, `semanage`.
> Maggiori informazioni: <https://manned.org/semodule>.

- Elenca tutti i moduli di politiche installati:

`sudo semodule {{[-l|--list]}}`

- Installa un nuovo modulo di politica:

`sudo semodule {{[-i|--install]}} {{percorso/del/modulo.pp}}`

- Rimuove un modulo di politica:

`sudo semodule {{[-r|--remove]}} {{nome_modulo}}`

- Abilita un modulo di politica:

`sudo semodule {{[-e|--enable]}} {{nome_modulo}}`

- Disabilita un modulo di politica:

`sudo semodule {{[-d|--disable]}} {{nome_modulo}}`

- Ricarica tutti i moduli di politica:

`sudo semodule {{[-R|--reload]}}`

- Mostra la versione dei moduli di politica installati:

`sudo semodule {{[-l|--list]}} {{[-v|--verbose]}}`
