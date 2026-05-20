# lvrename

> Rinomina un volume logico.
> Maggiori informazioni: <https://manned.org/lvrename>.

- Rinomina un LV usando percorsi completi:

`sudo lvrename {{/dev/vg_name/old_lv}} {{/dev/vg_name/new_lv}}`

- Rinomina un LV usando il gruppo di volumi e i nomi:

`sudo lvrename {{vg_name}} {{old_lv}} {{new_lv}}`

- Risponde "sì" a qualsiasi prompt:

`sudo lvrename {{[-y|--yes]}} {{/dev/vg_name/old_lv}} {{/dev/vg_name/new_lv}}`
