# dget

> Scarica pacchetti Debian.
> Maggiori informazioni: <https://manned.org/dget>.

- Scarica un pacchetto binario:

`dget {{package}}`

- Scarica ed estrae un pacchetto sorgente dal suo file `.dsc`:

`dget {{http://deb.debian.org/debian/pool/main/h/haskell-tldr/haskell-tldr_0.4.0-2.dsc}}`

- Scarica un tarball del pacchetto sorgente dal suo file `.dsc` ma non lo estrae:

`dget {{[-d|--download-only]}} {{http://deb.debian.org/debian/pool/main/h/haskell-tldr/haskell-tldr_0.4.0-2.dsc}}`
