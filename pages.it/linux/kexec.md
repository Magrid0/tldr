# kexec

> Riavvia direttamente in un nuovo kernel.
> Maggiori informazioni: <https://manned.org/kexec>.

- Carica un nuovo kernel:

`kexec {{[-l|--load]}} {{path/to/kernel}} --initrd={{path/to/initrd}} --command-line={{arguments}}`

- Carica un nuovo kernel con i parametri di avvio correnti:

`kexec {{[-l|--load]}} {{path/to/kernel}} --initrd={{path/to/initrd}} --reuse-cmdline`

- Esegue un kernel attualmente caricato:

`kexec {{[-e|--exec]}}`

- Scarica il kernel target kexec corrente:

`kexec {{[-u|--unload]}}`
