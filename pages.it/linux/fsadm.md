# fsadm

> Controlla o ridimensiona un filesystem su un dispositivo.
> Maggiori informazioni: <https://manned.org/fsadm>.

- Controlla un filesystem per errori:

`fsadm check {{/dev/vg_name/lv_name}}`

- Esegue un ridimensionamento di prova a una dimensione specifica (nessuna modifica effettiva):

`fsadm {{[-n|--dry-run]}} resize {{/dev/vg_name/lv_name}} {{10G}}`

- Espande un filesystem per riempire l'intero dispositivo (ometti la dimensione):

`fsadm resize {{/dev/vg_name/lv_name}}`

- Ridimensiona il filesystem e il volume logico sottostante insieme:

`fsadm {{[-l|--lvresize]}} resize {{/dev/vg_name/lv_name}} {{100G}}`

- Per ext2/3/4, smonta e ridimensiona offline:

`fsadm {{[-e|--ext-offline]}} resize {{/dev/vg_name/lv_name}} {{20G}}`
