# ldapdomaindump

> Scarica informazioni su utenti, computer, gruppi, sistemi operativi e appartenenze tramite LDAP in output HTML, JSON e greppabile.
> Vedi anche: `ldapsearch`.
> Maggiori informazioni: <https://github.com/dirkjanm/ldapdomaindump#usage>.

- Scarica tutte le informazioni usando l'account LDAP specificato:

`ldapdomaindump {{[-u|--user]}} {{domain}}\{{username}} {{[-p|--password]}} {{password|ntlm_hash}} {{hostname|ip}}`

- Scarica tutte le informazioni, risolvendo gli hostname dei computer:

`ldapdomaindump {{[-r|--resolve]}} {{[-u|--user]}} {{domain}}\{{username}} {{[-p|--password]}}{{password}} {{hostname|ip}}`

- Scarica tutte le informazioni, risolvendo gli hostname dei computer con il server DNS selezionato:

`ldapdomaindump {{[-r|--resolve]}} {{[-n|--dns-server]}} {{domain_controller_ip}} {{[-u|--user]}} {{domain}}\{{username}} {{[-p|--password]}}{{password}} {{hostname|ip}}`

- Scarica tutte le informazioni nella directory data senza output JSON:

`ldapdomaindump --no-json {{[-o|--outdir]}} {{path/to/directory}} {{[-u|--user]}} {{domain}}\{{username}} {{[-p|--password]}}{{password}} {{hostname|ip}}`
