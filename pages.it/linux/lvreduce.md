# lvreduce

> Riduce la dimensione di un volume logico.
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/lvreduce>.

- Riduce la dimensione di un volume a 120 GB:

`sudo lvreduce {{[-L|--size]}} {{120G}} {{logical_volume}}`

- Riduce la dimensione di un volume di 40 GB e anche il filesystem sottostante:

`sudo lvreduce {{[-L|--size]}} -{{40G}} {{[-r|--resizefs]}} {{logical_volume}}`
