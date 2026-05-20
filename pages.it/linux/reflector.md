# reflector

> Script Arch per recuperare e ordinare gli specchi dei mirror.
> Maggiori informazioni: <https://manned.org/reflector>.

- Ottiene tutti i mirror, ordinati per velocità di download e li salva:

`sudo reflector --sort {{rate}} --save {{/etc/pacman.d/mirrorlist}}`

- Ottiene solo i mirror HTTPS tedeschi:

`reflector {{[-c|--country]}} {{Germany}} {{[-p|--protocol]}} {{https}}`

- Ottiene solo i 10 mirror sincronizzati più di recente:

`reflector {{[-l|--latest]}} {{10}}`

- Usa un file di configurazione per recuperare i mirror:

`sudo reflector @{{/etc/xdg/reflector/reflector.conf}}`

- Mostra aiuto:

`reflector {{[-h|--help]}}`
