# uuid

> Genera e decodifica UUID (Universally Unique Identifiers).
> Vedi anche: `uuidgen`.
> Maggiori informazioni: <https://manned.org/uuid>.

- Genera un UUIDv1 (basato sul tempo e sull'indirizzo hardware del sistema, se presente):

`uuid`

- Genera un UUIDv4 (basato su dati casuali):

`uuid -v {{4}}`

- Genera più identificatori UUIDv4 contemporaneamente:

`uuid -v {{4}} -n {{numero_di_uuid}}`

- Genera un UUIDv4 e specifica il formato di output:

`uuid -v {{4}} -F {{BIN|STR|SIV}}`

- Genera un UUIDv4 e scrivi l'output in un file:

`uuid -v {{4}} -o {{percorso/del/file}}`

- Genera un UUIDv5 (basato sul nome dell'oggetto fornito) con un prefisso di namespace specificato:

`uuid -v {{5}} ns:{{DNS|URL|OID|X500}} {{nome_oggetto}}`

- Decodifica un UUID dato:

`uuid -d {{uuid}}`
