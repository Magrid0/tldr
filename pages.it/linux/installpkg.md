# installpkg

> Installa un pacchetto Slackware.
> Maggiori informazioni: <https://www.slackbook.org/html/book.html#PACKAGE-MANAGEMENT-PACKAGE-UTILITIES-INSTALLPKG>.

- Installa un pacchetto:

`sudo installpkg {{path/to/package.tgz}}`

- Genera un report di un'installazione simulata su `stdout`:

`installpkg -warn {{path/to/package.tgz}}`

- Crea un pacchetto dalla directory corrente e dalle sue sottodirectory:

`installpkg -m {{package_name.tgz}}`

- Installa il contenuto della directory corrente e delle sottodirectory come pacchetto con un nome specifico:

`sudo installpkg -r {{package_name.tgz}}`
