# avahi-browse

> Mostra servizi e host esposti sulla rete locale tramite mDNS/DNS-SD.
> Avahi è compatibile con Bonjour (Zeroconf) trovato nei dispositivi Apple.
> Maggiori informazioni: <https://manned.org/avahi-browse>.

- Elenca i servizi disponibili sulla rete locale insieme ai loro indirizzi e porte, ignorando quelli sulla macchina locale:

`avahi-browse {{[-a|--all]}} {{[-r|--resolve]}} {{[-l|--ignore-local]}}`

- Elenca rapidamente i servizi nella rete locale in formato SSV per script:

`avahi-browse {{[-a|--all]}} {{[-t|--terminate]}} {{[-p|--parsable]}}`

- Elenca i domini nelle vicinanze:

`avahi-browse {{[-D|--browse-domains]}}`

- Limita la ricerca a un dominio particolare:

`avahi-browse {{[-a|--all]}} --domain={{dominio}}`
