# intercept

> Legge eventi di input raw da un dispositivo di input specificato e li reindirizza a `stdout`.
> Maggiori informazioni: <https://gitlab.com/interception/linux/tools/-/tree/master#intercept>.

- Legge e outputta eventi di input raw da un dato file del dispositivo di input (il sistema non vedrà alcuna pressione di tasti):

`sudo intercept -g {{/dev/input/eventX}}`

- Legge e outputta eventi di input raw da un dato file del dispositivo di input (il sistema può vedere le pressioni di tasti e non blocca altri programmi dalla loro lettura):

`sudo intercept {{/dev/input/eventX}}`
