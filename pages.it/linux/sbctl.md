# sbctl

> Un gestore di chiavi secure boot facile da usare.
> Nota: non registrare i certificati Microsoft può danneggiare il sistema. Vedi <https://github.com/Foxboron/sbctl/wiki/FAQ#option-rom>.
> Maggiori informazioni: <https://github.com/Foxboron/sbctl#usage>.

- Mostra lo stato corrente del secure boot:

`sbctl status`

- Crea chiavi secure boot personalizzate (di default, tutto è archiviato in `/var/lib/sbctl`):

`sbctl create-keys`

- Registra le chiavi secure boot personalizzate e i certificati UEFI Microsoft:

`sbctl enroll-keys {{[-m|--microsoft]}}`

- Esegue automaticamente `create-keys` e `enroll-keys` in base alle impostazioni in `/etc/sbctl/sbctl.conf`:

`sbctl setup --setup`

- Firma un binario EFI con la chiave creata e salva il file nel database:

`sbctl sign {{[-s|--save]}} {{percorso/del/binario_efi}}`

- Rifirma tutti i file salvati:

`sbctl sign-all`

- Verifica che tutti gli eseguibili EFI sulla partizione di sistema EFI siano stati firmati:

`sbctl verify`
