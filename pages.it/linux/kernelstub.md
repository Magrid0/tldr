# kernelstub

> Gestisce automaticamente il caricamento del kernel Linux su (U)EFI.
> Maggiori informazioni: <https://github.com/isantop/kernelstub#usage>.

- Configura il kernel corrente con opzioni predefinite:

`sudo kernelstub`

- Aggiunge opzioni kernel personalizzate:

`sudo kernelstub {{[-o|--options]}} "{{quiet splash mitigations=off}}"`

- Esegue in modalità verbosa con configurazione `systemd-boot`:

`sudo kernelstub {{[-v|--verbose]}} {{[-l|--loader]}}`

- Copia solo il kernel in ESP senza modifiche NVRAM:

`sudo kernelstub {{[-m|--manage-only]}}`

- Esegue una simulazione senza apportare modifiche (prova a vuoto):

`sudo kernelstub {{[-c|--dry-run]}}`

- Specifica i percorsi manualmente:

`sudo kernelstub {{[-k|--kernel-path]}} /{{path/to/vmlinuz}} {{[-i|--initrd-path]}} /{{path/to/initrd.img}} {{[-e|--esp-path]}} /{{path/to/efi_partition}}`

- Mostra la configurazione corrente:

`sudo kernelstub {{[-p|--print-config]}}`
