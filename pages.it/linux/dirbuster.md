# dirbuster

> Esegue brute-force su directory e nomi di file su server.
> Maggiori informazioni: <https://www.kali.org/tools/dirbuster/>.

- Avvia in modalità GUI:

`dirbuster -u {{http://example.com}}`

- Avvia in modalità headless (senza GUI):

`dirbuster -H -u {{http://example.com}}`

- Imposta l'elenco delle estensioni file:

`dirbuster -e {{txt,html}}`

- Abilita output verboso:

`dirbuster -v`

- Imposta la posizione del report:

`dirbuster -r {{path/to/report.txt}}`
