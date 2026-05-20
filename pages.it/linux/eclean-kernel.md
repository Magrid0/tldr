# eclean-kernel

> Rimuove i vecchi kernel in Gentoo.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Kernel/Removal#Using_eclean-kernel>.

- Elenca tutti i file del kernel:

`sudo eclean-kernel {{[-l|--list-kernels]}}`

- Rimuove tutti i kernel tranne i due più recenti:

`sudo eclean-kernel {{[-n|--num]}} 2`

- Rimuove tutti i kernel tranne i due più recenti e chiede conferma prima della rimozione:

`sudo eclean-kernel {{[-a|--all]}} {{[-n|--num]}} 2`
