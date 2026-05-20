# rpmkeys

> Strumento per importare e rimuovere chiavi RPM per repository RPM.
> Quando si aggiunge un repository RPM, è necessario importare anche la chiave RPM corrispondente.
> Maggiori informazioni: <https://rpm-software-management.github.io/rpm/man/rpmkeys.8>.

- Elenca tutte le chiavi RPM importate. Mostra anche il suo Key ID necessario per eliminare una chiave RPM importata:

`sudo rpmkeys --list`

- Rimuove/Elimina una chiave RPM importata in precedenza, data dal suo Key ID di 16 numeri/lettere:

`sudo rpmkeys --delete {{5a278d9c-5bbc73cb}}`

- Importa una chiave RPM del repository:

`sudo rpmkeys --import {{path/to/rpm_key}}`
