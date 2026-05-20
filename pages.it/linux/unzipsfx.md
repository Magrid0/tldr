# unzipsfx

> Crea un file binario compresso autoestraente anteponendo stub autoestraenti a un file Zip.
> Maggiori informazioni: <https://manned.org/unzipsfx>.

- Crea un file binario autoestraente da un archivio Zip:

`cat $(which unzipsfx) {{percorso/dell/archivio.zip}} > {{nome_file}} && chmod 755 {{nome_file}}`

- Estrae un binario autoestraente nella directory corrente:

`{{./percorso/del/binario}}`

- Testa un binario autoestraente per errori:

`{{./percorso/del/binario}} -t`

- Stampa il contenuto di un file nel binario autoestraente senza estrazione:

`{{./percorso/del/binario}} -c {{percorso/del/file}}`

- Stampa i commenti sull'archivio Zip nel binario autoestraente:

`{{./percorso/del/binario}} -z`
