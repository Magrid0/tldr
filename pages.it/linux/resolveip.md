# resolveip

> Risolve i nomi host nei loro indirizzi IP e viceversa.
> Maggiori informazioni: <https://mariadb.com/docs/server/clients-and-utilities/networking-tools/resolveip>.

- Risolve un nome host in un indirizzo IP:

`resolveip {{example.org}}`

- Risolve un indirizzo IP in un nome host:

`resolveip {{1.1.1.1}}`

- Risolve un nome host in un indirizzo IP con output ridotto:

`resolveip {{[-s|--silent]}} {{example.org}}`
