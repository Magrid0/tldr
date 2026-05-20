# obabel

> Traduce dati relativi alla chimica.
> Maggiori informazioni: <https://open-babel.readthedocs.io/en/latest/Command-line_tools/babel.html>.

- Converte un file `.mol` in coordinate XYZ:

`obabel {{percorso/del/file.mol}} -O {{percorso/del/file_output.xyz}}`

- Converte una stringa SMILES in un'immagine 500x500:

`obabel -:"{{SMILES}}" -O {{percorso/del/file_output.png}} -xp 500`

- Converte un file di stringhe SMILES in file `.mol` 3D separati:

`obabel {{percorso/del/file.smi}} -O {{percorso/del/file_output.mol}} --gen3D -m`

- Renderizza più input in un'unica immagine:

`obabel {{percorso/del/file1 percorso/del/file2 ...}} -O {{percorso/del/file_output.png}}`
