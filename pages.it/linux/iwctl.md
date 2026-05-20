# iwctl

> Controlla il supplicant di rete `iwd`.
> Vedi anche: `nmcli`, `iw`.
> Maggiori informazioni: <https://manned.org/iwctl>.

- Esegue `iwctl` in modalità interattiva:

`iwctl`

- Mostra le stazioni Wi-Fi:

`iwctl station list`

- Cerca reti con una stazione:

`iwctl station {{station}} scan`

- Mostra le reti trovate da una stazione:

`iwctl station {{station}} get-networks`

- Si connette a una rete con una stazione, se sono necessarie credenziali verranno chieste:

`iwctl station {{station}} connect {{network_name}}`

- Mostra aiuto:

`iwctl {{[-h|--help]}}`
