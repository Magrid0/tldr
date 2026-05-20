# lvchange

> Modifica gli attributi o lo stato di attivazione dei volumi logici.
> Maggiori informazioni: <https://manned.org/lvchange>.

- Attiva un volume logico:

`sudo lvchange {{[-a|--activate]}} y {{/dev/vg_name/lv_name}}`

- Disattiva un volume logico:

`sudo lvchange {{[-a|--activate]}} n {{/dev/vg_name/lv_name}}`

- Abilita l'attivazione automatica per un volume logico:

`sudo lvchange {{[-a|--activate]}} ay {{/dev/vg_name/lv_name}}`

- Imposta un volume logico in sola lettura (usa `rw` per lettura-scrittura):

`sudo lvchange {{[-p|--permission]}} r {{/dev/vg_name/lv_name}}`

- Salta l'attivazione per un volume logico:

`sudo lvchange {{[-k|--setactivationskip]}} y {{/dev/vg_name/lv_name}}`

- Aggiorna un volume logico usando i metadati più recenti:

`sudo lvchange --refresh {{/dev/vg_name/lv_name}}`
