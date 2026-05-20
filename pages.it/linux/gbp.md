# gbp

> Sistema per integrare il sistema di compilazione dei pacchetti Debian con Git.
> Maggiori informazioni: <https://honk.sigxcpu.org/projects/git-buildpackage/manual-html/gbp.html>.

- Converte un pacchetto Debian esistente in gbp:

`gbp import-dsc {{path/to/package.dsc}}`

- Compila il pacchetto nella directory corrente usando il compilatore predefinito (`debuild`):

`gbp buildpackage -jauto -us -uc`

- Compila un pacchetto in un ambiente `pbuilder` per Debian Bullseye:

`DIST={{bullseye}} ARCH={{amd64}} gbp buildpackage -jauto -us -uc --git-builder={{git-pbuilder}}`

- Specifica un pacchetto come upload di solo sorgente nel file `.changes` (vedi <https://wiki.debian.org/SourceOnlyUpload>):

`gbp buildpackage -jauto -us -uc --changes-options={{-S}}`

- Importa una nuova release upstream:

`gbp import-orig --pristine-tar {{path/to/package.tar.gz}}`
