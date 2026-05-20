# systemd-cryptenroll

> Iscrive o rimuove in modo interattivo metodi utilizzati per sbloccare dispositivi crittografati LUKS2. Utilizza una password per sbloccare il dispositivo, salvo diversa indicazione.
> Per consentire lo sblocco di una partizione durante l'avvio del sistema, aggiornare il file `/etc/crypttab` o l'initramfs.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-cryptenroll.html>.

- Iscrive una nuova password (simile a `cryptsetup luksAddKey`):

`systemd-cryptenroll --password {{percorso/del/dispositivo_a_blocchi_luks2}}`

- Iscrive una nuova chiave di ripristino (ovvero una passphrase generata casualmente utilizzabile come fallback):

`systemd-cryptenroll --recovery-key {{percorso/del/dispositivo_a_blocchi_luks2}}`

- Elenca i token disponibili o iscrive un nuovo token PKCS#11:

`systemd-cryptenroll --pkcs11-token-uri {{list|auto|uri_token_pkcs11}} {{percorso/del/dispositivo_a_blocchi_luks2}}`

- Elenca i dispositivi FIDO2 disponibili o iscrive un nuovo dispositivo FIDO2 (`auto` può essere usato come nome del dispositivo quando è collegato un solo token):

`systemd-cryptenroll --fido2-device {{list|auto|percorso/del/dispositivo_hidraw_fido2}} {{percorso/del/dispositivo_a_blocchi_luks2}}`

- Iscrive un nuovo dispositivo FIDO2 con verifica utente (biometria):

`systemd-cryptenroll --fido2-device {{auto|percorso/del/dispositivo_hidraw_fido2}} --fido2-with-user-verification yes {{percorso/del/dispositivo_a_blocchi_luks2}}`

- Sblocca utilizzando un dispositivo FIDO2 e iscrive un nuovo dispositivo FIDO2:

`systemd-cryptenroll --unlock-fido2-device {{percorso/del/dispositivo_hidraw_fido2_sblocco}} --fido2-device {{percorso/del/dispositivo_hidraw_fido2_iscrizione}} {{percorso/del/dispositivo_a_blocchi_luks2}}`

- Iscrive un chip di sicurezza TPM2 (solo PCR secure-boot-policy) e richiede un PIN alfanumerico aggiuntivo:

`systemd-cryptenroll --tpm2-device {{auto|percorso/del/dispositivo_a_blocchi_tpm2}} --tpm2-with-pin yes {{percorso/del/dispositivo_a_blocchi_luks2}}`

- Rimuove tutte le password vuote/tutte le password/tutti i dispositivi FIDO2/tutti i token PKCS#11/tutti i chip di sicurezza TPM2/tutte le chiavi di ripristino/tutti i metodi:

`systemd-cryptenroll --wipe-slot {{empty|password|fido2|pkcs#11|tpm2|recovery|all}} {{percorso/del/dispositivo_a_blocchi_luks2}}`
