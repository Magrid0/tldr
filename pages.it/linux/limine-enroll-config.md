# limine-enroll-config

> Incorpora o reimposta l'hash BLAKE2B di `limine.conf` nell'eseguibile EFI di Limine.
> Usato per garantire che il file di configurazione non sia stato manomesso quando Secure Boot è abilitato.
> Maggiori informazioni: <https://codeberg.org/Limine/Limine/src/branch/trunk/USAGE.md#secure-boot>.

- Incorpora l'hash BLAKE2B di un file di configurazione nell'eseguibile EFI di Limine:

`limine-enroll-config {{path/to/BOOTX64.EFI}} {{blake2b_hash}}`

- Rimuove l'hash incorporato dall'eseguibile, disabilitando il controllo di integrità della configurazione:

`limine-enroll-config --reset {{path/to/BOOTX64.EFI}}`

- Mostra aiuto:

`limine-enroll-config --help`
