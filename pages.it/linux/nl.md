# nl

> Numera le righe da un file o da `stdin`.
> Maggiori informazioni: <https://manned.org/nl>.

- Numera le righe non vuote in un file:

`nl {{percorso/del/file}}`

- Legge da `stdin`:

`{{comando}} | nl`

- Numera [t]utte le righe del corpo incluse le righe vuote o [n]on numerare le righe del corpo:

`nl {{[-b|--body-numbering]}} {{a|n}} {{percorso/del/file}}`

- Numera solo le righe del corpo che corrispondono a un `regex` di base (BRE) [p]attern:

`nl {{[-b|--body-numbering]}} p'FooBar[0-9]' {{percorso/del/file}}`

- Usa un incremento specifico per la numerazione delle righe:

`nl {{[-i|--line-increment]}} {{incremento}} {{percorso/del/file}}`

- Specifica il formato di numerazione delle righe [d]estro o [s]inistro, mantenendo gli [z]eri iniziali o [n]o:

`nl {{[-n|--number-format]}} {{rz|ln|rn}}`

- Specifica la larghezza della numerazione delle righe (6 per impostazione predefinita):

`nl {{[-w|--number-width]}} {{larghezza_col}} {{percorso/del/file}}`

- Usa una stringa specifica per separare i numeri di riga dalle righe (`TAB` per impostazione predefinita):

`nl {{[-s|--number-separator]}} {{separatore}} {{percorso/del/file}}`
