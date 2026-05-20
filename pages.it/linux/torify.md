# torify

> Instrada il traffico di rete attraverso la rete Tor.
> Nota: Questo comando è stato deprecato ed è ora un wrapper retrocompatibile di `torsocks`.
> Maggiori informazioni: <https://manned.org/torify>.

- Instrada il traffico via Tor:

`torify {{comando}}`

- Attiva/disattiva Tor nella shell:

`torify {{on|off}}`

- Avvia una shell abilitata a Tor:

`torify --shell`

- Verifica la presenza di una shell abilitata a Tor:

`torify show`

- Specifica il file di configurazione di Tor:

`torify -c {{file_configurazione}} {{comando}}`

- Utilizza un proxy SOCKS Tor specifico:

`torify -P {{proxy}} {{comando}}`

- Reindirizza l'output in un file:

`torify {{comando}} > {{percorso/di/output}}`
