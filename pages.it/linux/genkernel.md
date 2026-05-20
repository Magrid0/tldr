# genkernel

> Utilità Gentoo Linux per compilare e installare kernel.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Genkernel>.

- Compila e installa automaticamente un kernel generico:

`sudo genkernel all`

- Compila e installa solo il bzImage, initramfs, kernel o ramdisk:

`sudo genkernel {{bzImage|initramfs|kernel|ramdisk}}`

- Applica modifiche alla configurazione del kernel prima di compilare e installare:

`sudo genkernel --menuconfig all`

- Genera un kernel con un nome personalizzato:

`sudo genkernel --kernname={{custom_name}} all`

- Usa un sorgente del kernel al di fuori della directory predefinita `/usr/src/linux`:

`sudo genkernel --kerneldir={{path/to/directory}} all`
