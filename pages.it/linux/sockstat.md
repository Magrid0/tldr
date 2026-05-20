# sockstat

> Elenca i socket aperti Internet o UNIX domain.
> Vedi anche: `netstat`.
> Maggiori informazioni: <https://manned.org/sockstat>.

- Mostra informazioni per socket IPv4 e IPv6 sia in ascolto che connessi:

`sockstat`

- Mostra informazioni per socket IPv[4]/IPv[6] in [a]scolto su [p]orte specifiche usando un p[R]otocollo specifico:

`sockstat -{{4|6}} -l -R {{tcp|udp|raw|unix}} -p {{porta1,porta2...}}`

- Mostra anche socket [c]onnessi e socket [u]nix:

`sockstat -cu`

- Mostra solo socket del `pid` o processo specificato:

`sockstat -P {{pid|processo}}`

- Mostra solo socket dell'`uid` o utente specificato:

`sockstat -U {{uid|utente}}`

- Mostra solo socket del `gid` o gruppo specificato:

`sockstat -G {{gid|gruppo}}`
