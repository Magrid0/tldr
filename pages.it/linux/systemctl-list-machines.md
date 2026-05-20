# systemctl list-machines

> Elenca l'host e tutte le macchine virtuali locali o container in esecuzione con il loro stato.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#list-machines%20PATTERN%E2%80%A6>.

- Mostra tutte le macchine (host e container/VM in esecuzione):

`systemctl list-machines`

- Elenca una macchina specifica:

`systemctl list-machines {{macchina}}`

- Elenca più macchine corrispondenti:

`systemctl list-machines {{macchina_1 macchina_2 ...}}`

- Filtra le macchine usando pattern wildcard, ad esempio `shell-globbing`:

`systemctl list-machines {{pattern}}`
