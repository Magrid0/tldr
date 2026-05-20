# locate

> Trova rapidamente i nomi dei file.
> Maggiori informazioni: <https://manned.org/locate>.

- Cerca un pattern nel database. Nota: Il database viene ricalcolato periodicamente (di solito settimanalmente o giornalmente):

`locate "{{pattern}}"`

- Cerca un pattern senza distinzione tra maiuscole e minuscole:

`locate {{[-i|--ignore-case]}} "{{pattern}}"`

- Cerca un file con il suo nome esatto (un pattern senza caratteri glob viene interpretato come `*pattern*`):

`locate "*/{{filename}}"`

- Ricalcola il database. È necessario farlo per trovare file aggiunti di recente:

`sudo updatedb`
