# authconfig

> Configura le risorse di autenticazione del sistema.
> Maggiori informazioni: <https://manned.org/authconfig>.

- Mostra la configurazione corrente (o prova a secco):

`authconfig --test`

- Configura il server per utilizzare un diverso algoritmo di hashing delle password:

`authconfig --update --passalgo={{algoritmo}}`

- Abilita l'autenticazione LDAP:

`authconfig --update --enableldapauth`

- Disabilita l'autenticazione LDAP:

`authconfig --update --disableldapauth`

- Abilita il Network Information Service (NIS):

`authconfig --update --enablenis`

- Abilita Kerberos:

`authconfig --update --enablekrb5`

- Abilita l'autenticazione Winbind (Active Directory):

`authconfig --update --enablewinbindauth`

- Abilita l'autorizzazione locale:

`authconfig --update --enablelocauthorize`
