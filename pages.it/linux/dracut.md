# dracut

> Genera immagini initramfs per avviare il kernel Linux.
> Dracut usa opzioni da file di configurazione in `/etc/dracut.conf`, `/etc/dracut.conf.d/*.conf` e `/usr/lib/dracut/dracut.conf.d/*.conf` di default.
> Maggiori informazioni: <https://github.com/dracut-ng/dracut-ng/blob/main/man/dracut.8.adoc>.

- Genera un'immagine initramfs per il kernel corrente senza ignorare alcuna opzione:

`dracut`

- Genera un'immagine initramfs per il kernel corrente e sovrascrive quella esistente:

`dracut {{[-f|--force]}}`

- Genera un'immagine initramfs per un kernel specifico:

`dracut --kver {{kernel_version}}`

- Elenca i moduli disponibili:

`dracut --list-modules`
