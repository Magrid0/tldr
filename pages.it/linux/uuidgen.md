# uuidgen

> Genera identificatori unici (UUID).
> Vedi anche: `uuid`.
> Maggiori informazioni: <https://manned.org/uuidgen>.

- Crea un UUIDv4 casuale:

`uuidgen {{[-r|--random]}}`

- Crea un UUIDv1 basato sull'ora corrente:

`uuidgen {{[-t|--time]}}`

- Crea un UUIDv5 del nome con un prefisso di namespace specificato:

`uuidgen {{[-s|--sha1]}} {{[-n|--namespace]}} {{@dns|@url|@oid|@x500}} {{[-N|--name]}} {{nome_oggetto}}`
