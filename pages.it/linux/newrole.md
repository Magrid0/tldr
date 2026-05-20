# newrole

> Avvia una nuova shell con un ruolo SELinux diverso.
> Permette agli utenti di cambiare contesto di sicurezza SELinux.
> Vedi anche: `runcon`, `semanage-user`.
> Maggiori informazioni: <https://manned.org/newrole>.

- Avvia una nuova shell con un ruolo SELinux specifico:

`newrole {{[-r|--role]}} {{nome_ruolo}}`

- Avvia una nuova shell con un tipo SELinux specifico:

`newrole {{[-t|--type]}} {{nome_tipo}}`

- Avvia una nuova shell con un livello SELinux specifico (formato: `s0-s0:c0.c1023`; livelli da `s0` a `s15`, `-` per intervallo, `c` per categorie, `:` separa livello da categorie, `.` per intervallo di categorie):

`newrole {{[-l|--level]}} {{s0-s0:c0.c1023}}`

- Mostra il contesto SELinux corrente:

`id {{[-Z|--context]}}`

- Avvia una nuova shell con sia ruolo che tipo:

`newrole {{[-r|--role]}} {{nome_ruolo}} {{[-t|--type]}} {{nome_tipo}}`
