# oniux

> Isola un'applicazione arbitraria e instrada il traffico attraverso la rete Tor.
> Nota: Questo è un software sperimentale.
> Maggiori informazioni: <https://gitlab.torproject.org/tpo/core/oniux>.

- Isola un'applicazione:

`oniux {{comando}}`

- Interroga un sito web:

`oniux curl {{https://example.com}}`

- Interroga un sito onion:

`oniux curl {{http://example.onion}}`

- Esegue un'intera shell in isolamento "torificato":

`oniux bash`

- Isola applicazioni grafiche in ambienti desktop:

`oniux hexchat`
