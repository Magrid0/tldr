# xclip

> Strumento di manipolazione degli appunti X11, simile a `xsel`.
> Gestisce le selezioni primaria e secondaria di X, più gli appunti di sistema (`<Ctrl c>`/`<Ctrl v>`).
> Vedi anche: `wl-copy`.
> Maggiori informazioni: <https://manned.org/xclip>.

- Copia l'output di un comando nell'area di selezione primaria X11 (appunti):

`echo 123 | xclip`

- Copia l'output di un comando in una data area di selezione X11:

`echo 123 | xclip {{[-se|-selection]}} {{primary|secondary|clipboard}}`

- Copia l'output di un comando negli appunti di sistema, usando la notazione breve:

`echo 123 | xclip {{[-se|-selection]}} {{[c|clipboard]}}`

- Copia il contenuto di un file negli appunti di sistema:

`xclip {{[-se|-selection]}} {{[c|clipboard]}} {{path/to/file_input.txt}}`

- Copia il contenuto di un PNG negli appunti di sistema (può essere incollato correttamente in altri programmi):

`xclip {{[-se|-selection]}} {{[c|clipboard]}} {{[-t|-target]}} image/png {{path/to/file_input.png}}`

- Copia l'input dell'utente nella console negli appunti di sistema:

`xclip {{[-i|-in]}}`

- Incolla il contenuto dell'area di selezione primaria X11 nella console:

`xclip {{[-o|-out]}}`

- Incolla il contenuto degli appunti di sistema nella console:

`xclip {{[-o|-out]}} {{[-se|-selection]}} {{[c|clipboard]}}`
