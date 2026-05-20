# sqfstar

> Crea un filesystem squashfs da un archivio `.tar`.
> Maggiori informazioni: <https://manned.org/sqfstar>.

- Crea un filesystem squashfs (compresso usando `gzip` per impostazione predefinita) da un archivio `.tar` non compresso:

`sqfstar < {{archive.tar}} {{filesystem.squashfs}}`

- Crea un filesystem squashfs da un archivio `.tar` compresso con `gzip`, e [comp]rime il filesystem usando un algoritmo specifico:

`zcat {{archive.tar.gz}} | sqfstar -comp {{gzip|lzo|lz4|xz|zstd|lzma}} {{filesystem.squashfs}}`

- Crea un filesystem squashfs da un archivio `.tar` compresso con `xz`, escludendo alcuni file:

`xzcat {{archive.tar.xz}} | sqfstar {{filesystem.squashfs}} {{file1 file2 ...}}`

- Crea un filesystem squashfs da un archivio `.tar` compresso con `zstd`, escludendo i file che finiscono con `.gz`:

`zstdcat {{archive.tar.zst}} | sqfstar {{filesystem.squashfs}} "{{*.gz}}"`

- Crea un filesystem squashfs da un archivio `.tar` compresso con `lz4`, escludendo i file che corrispondono a un `regex`:

`lz4cat {{archive.tar.lz4}} | sqfstar {{filesystem.squashfs}} -regex "{{regex}}"`
