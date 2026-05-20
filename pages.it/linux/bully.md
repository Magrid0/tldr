# bully

> Esegue un attacco brute-force sul pin WPS di un punto di accesso wireless.
> Le informazioni necessarie devono essere raccolte con `airmon-ng` e `airodump-ng` prima di usare `bully`.
> Maggiori informazioni: <https://salsa.debian.org/pkg-security-team/bully>.

- Cracca la password:

`bully {{[-b|--bssid]}} "{{mac}}" {{[-c|--channel]}} "{{channel}}" {{[-B|--bruteforce]}} "{{interface}}"`

- Mostra aiuto:

`bully {{[-h|--help]}}`
