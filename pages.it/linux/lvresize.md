# lvresize

> Cambia la dimensione di un volume logico.
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/lvresize>.

- Cambia la dimensione di un volume logico a 120 GB:

`sudo lvresize {{[-L|--size]}} 120G {{volume_group}}/{{logical_volume}}`

- Estende la dimensione di un volume logico e anche il filesystem sottostante di 120 GB:

`sudo lvresize {{[-L|--size]}} +120G {{[-r|--resizefs]}} {{volume_group}}/{{logical_volume}}`

- Estende la dimensione di un volume logico al 100% dello spazio libero del volume fisico:

`sudo lvresize {{[-l|--extents]}} 100%FREE {{volume_group}}/{{logical_volume}}`

- Riduce la dimensione di un volume logico e anche il filesystem sottostante di 120 GB:

`sudo lvresize {{[-L|--size]}} -120G {{[-r|--resizefs]}} {{volume_group}}/{{logical_volume}}`
