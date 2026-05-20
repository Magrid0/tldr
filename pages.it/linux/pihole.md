# pihole

> Gestisce il server DNS ad-blocking Pi-hole.
> Maggiori informazioni: <https://docs.pi-hole.net/main/pihole-command/>.

- Controlla lo stato di Pi-hole:

`pihole status`

- Aggiorna Pi-hole e Gravity:

`sudo pihole {{[-up|updatePihole]}}`

- Avvia o ferma il demone:

`pihole {{enable|disable}}`

- Aggiorna le liste e svuota la cache senza riavviare il server DNS:

`pihole reloaddns`

- Aggiorna la lista dei domini pubblicitari:

`pihole {{[-g|updateGravity]}}`

- Consenti o nega il dominio specificato:

`pihole {{allow|deny}} {{example.com}}`

- Cerca il dominio nelle liste:

`pihole {{[-q|query]}} {{example.com}}`

- Apre un log in tempo reale delle connessioni:

`pihole {{[-t|tail]}}`
