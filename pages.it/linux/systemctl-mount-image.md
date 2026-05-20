# systemctl mount-image

> Monta un file immagine nel namespace di mount di un'unità.
> Supportato solo per le unità che vengono eseguite all'interno di un mountspace, ad esempio con `RootImage=`, `PrivateMounts=`, ecc.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#mount-image%20UNIT%20IMAGE%20%5BPATH%20%5BPARTITION_NAME:MOUNT_OPTIONS%5D%5D>.

- Monta un'immagine in un percorso specifico all'interno del namespace di mount dell'unità:

`systemctl mount-image {{unità}} /{{percorso/dell/immagine}} /{{percorso/della/directory_interna_all_unità}}`

- Monta la partizione `root` dell'immagine con opzioni di sola lettura e no-setuid:

`systemctl mount-image {{unità}} /{{percorso/dell/immagine}} /{{percorso/della/directory_interna_all_unità}} root:ro,nosuid`

- Crea la directory di destinazione prima del montaggio:

`systemctl mount-image --mkdir {{unità}} /{{percorso/dell/immagine}} /{{percorso/della/directory_interna_all_unità}}`

- Monta un'immagine in sola lettura:

`systemctl mount-image --read-only {{unità}} /{{percorso/dell/immagine}} /{{percorso/della/directory_interna_all_unità}}`
