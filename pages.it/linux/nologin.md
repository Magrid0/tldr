# nologin

> Shell alternativa che impedisce a un utente di accedere.
> Maggiori informazioni: <https://manned.org/nologin.8>.

- Imposta la shell di login di un utente a `nologin` per impedire all'utente di accedere:

`chsh {{[-s|--shell]}} {{utente}} nologin`

- Personalizza il messaggio per gli utenti con shell di login `nologin`:

`echo "{{messaggio_login_negato}}" > /etc/nologin.txt`
