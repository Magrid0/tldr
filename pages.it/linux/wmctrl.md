# wmctrl

> CLI per X Window Manager.
> Maggiori informazioni: <https://manned.org/wmctrl>.

- Elenca tutte le finestre gestite dal window manager:

`wmctrl -l`

- Passa alla prima finestra il cui titolo (parziale) corrisponde:

`wmctrl -a {{titolo_finestra}}`

- Sposta una finestra nell'area di lavoro corrente, sollevala e dalle il focus:

`wmctrl -R {{titolo_finestra}}`

- Passa a un'area di lavoro:

`wmctrl -s {{numero_area_di_lavoro}}`

- Seleziona una finestra e attiva/disattiva la modalità a schermo intero:

`wmctrl -r {{titolo_finestra}} -b toggle,fullscreen`

- Seleziona una finestra e spostala in un'area di lavoro:

`wmctrl -r {{titolo_finestra}} -t {{numero_area_di_lavoro}}`
