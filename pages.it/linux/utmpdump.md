# utmpdump

> Scarica e carica file di accounting btmp, utmp e wtmp.
> Maggiori informazioni: <https://manned.org/utmpdump>.

- Scarica il file `/var/log/wtmp` su `stdout` come testo semplice:

`utmpdump {{/var/log/wtmp}}`

- Carica un file precedentemente scaricato in `/var/log/wtmp`:

`utmpdump {{[-r|--reverse]}} {{file_dump}} > {{/var/log/wtmp}}`
