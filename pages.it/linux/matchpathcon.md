# matchpathcon

> Cerca l'impostazione persistente del contesto di sicurezza SELinux di un percorso.
> Vedi anche: `semanage-fcontext`, `secon`, `chcon`, `restorecon`.
> Maggiori informazioni: <https://manned.org/matchpathcon.8>.

- Cerca l'impostazione persistente del contesto di sicurezza di un percorso assoluto:

`matchpathcon /{{path/to/file}}`

- Limita la ricerca alle impostazioni su un tipo di file specifico:

`matchpathcon -m {{file|dir|pipe|chr_file|blk_file|lnk_file|sock_file}} /{{path/to/file}}`

- [V]erifica che il contesto di sicurezza persistente e corrente di un percorso corrispondano:

`matchpathcon -V /{{path/to/file}}`
