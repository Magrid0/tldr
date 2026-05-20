# lsfd

> Elenca i file aperti e i processi corrispondenti in Linux.
> Maggiori informazioni: <https://manned.org/lsfd>.

- Elenca tutti i descrittori di file aperti:

`lsfd`

- Elenca tutti i file tenuti aperti da un programma specifico:

`lsfd {{[-Q|--filter]}} 'PID == {{process_id}}'`

- Controlla quale programma ha un file specifico aperto:

`lsfd {{[-Q|--filter]}} "NAME == '{{path/to/file}}'"`

- Elenca i socket IPv4 o IPv6 aperti:

`lsfd {{-i4|-i6}}`

- Mostra aiuto:

`lsfd {{[-h|--help]}}`
