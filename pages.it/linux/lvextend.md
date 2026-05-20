# lvextend

> Aumenta la dimensione di un volume logico.
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/lvextend>.

- Aumenta la dimensione di un volume a 120 GB:

`sudo lvextend {{[-L|--size]}} {{120G}} {{logical_volume}}`

- Aumenta la dimensione di un volume di 40 GB e anche il filesystem sottostante:

`sudo lvextend {{[-L|--size]}} +{{40G}} {{[-r|--resizefs]}} {{logical_volume}}`

- Aumenta la dimensione di un volume al 100% dello spazio libero del volume fisico:

`sudo lvextend {{[-l|--extents]}} +{{100}}%FREE {{logical_volume}}`

- Aumenta la dimensione di un volume al 100% dello spazio libero del volume fisico e ridimensiona il filesystem sottostante:

`sudo lvextend {{[-l|--extents]}} +{{100}}%FREE {{[-r|--resizefs]}} {{logical_volume}}`
