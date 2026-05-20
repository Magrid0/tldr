# checkinstall

> Tiene traccia dell'installazione locale di un pacchetto software e produce un pacchetto binario utilizzabile con il gestore di pacchetti nativo del sistema.
> Maggiori informazioni: <https://checkinstall.izto.org/docs.php>.

- Crea e installa un pacchetto con le impostazioni predefinite:

`sudo checkinstall {{[-y|--default]}}`

- Crea un pacchetto senza installarlo:

`sudo checkinstall --install={{no}}`

- Crea un pacchetto senza documentazione:

`sudo checkinstall --nodoc`

- Crea un pacchetto e imposta il nome:

`sudo checkinstall --pkgname {{package}}`

- Crea un pacchetto e specifica dove salvarlo:

`sudo checkinstall --pakdir {{path/to/directory}}`
