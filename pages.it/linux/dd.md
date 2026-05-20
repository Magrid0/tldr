# dd

> Converte e copia un file.
> Vedi anche: `caligula`.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/dd-invocation.html>.

- Crea una chiavetta USB avviabile da un file isohybrid (come `archlinux-xxx.iso`) e mostra l'avanzamento:

`sudo dd if={{path/to/file.iso}} of={{/dev/usb_drive}} status=progress`

- Clona un'unità su un'altra unità con blocchi da 4 MiB e scarica le scritture prima che il comando termini:

`sudo dd bs=4M conv=fsync if={{/dev/source_drive}} of={{/dev/dest_drive}}`

- Genera un file con un numero specifico di byte casuali usando il driver random del kernel:

`dd bs={{100}} count={{1}} if=/dev/urandom of={{path/to/random_file}}`

- Testa le prestazioni di scrittura di un disco:

`dd bs={{1M}} count={{1024}} if=/dev/zero of={{path/to/file_1GB}}`

- Crea un backup di sistema, lo salva in un file IMG (può essere ripristinato scambiando `if` e `of`) e mostra l'avanzamento:

`sudo dd if={{/dev/drive_device}} of={{path/to/file.img}} status=progress`

- Controlla l'avanzamento di un'operazione `dd` in corso (esegui questo comando da un'altra shell):

`progress`
