# lspci

> Elenca tutti i dispositivi PCI.
> Maggiori informazioni: <https://manned.org/lspci>.

- Mostra un breve elenco di dispositivi:

`lspci`

- Mostra informazioni [v]erbose (Nota: il flag `-v` può essere ripetuto per aumentare la verbosità):

`lspci -v`

- Mostra i [k]ernel driver e moduli che gestiscono ogni dispositivo:

`lspci -k`

- [s]eleziona un dispositivo specifico:

`lspci -s {{00:18.3}}`

- Scarica le informazioni in forma ([m])achine leggibile:

`lspci -vm`

- Mostra i codici dei vendor e dispositivi PCI sia come [n]umeri che come [n]omi:

`lspci -nn`
