# macchanger

> Manipola gli indirizzi MAC delle interfacce di rete.
> Maggiori informazioni: <https://manned.org/macchanger>.

- Mostra gli indirizzi MAC corrente e permanente di un'interfaccia:

`macchanger {{[-s|--show]}} {{interface}}`

- Imposta un indirizzo MAC casuale per l'interfaccia:

`macchanger {{[-r|--random]}} {{interface}}`

- Imposta un indirizzo MAC casuale per l'interfaccia, fingendo di essere un indirizzo [b]urned-[i]n-[a]ddress:

`macchanger {{[-r|--random]}} {{[-b|--bia]}} {{interface}}`

- Imposta un indirizzo MAC specifico per l'interfaccia:

`macchanger {{[-m|--mac]}} {{XX:XX:XX:XX:XX:XX}} {{interface}}`

- Stampa le identificazioni (i primi tre byte di un indirizzo MAC) di tutti i vendor conosciuti:

`macchanger {{[-l|--list]}}`

- Ripristina l'interfaccia al suo indirizzo MAC hardware permanente:

`macchanger {{[-p|--permanent]}} {{interface}}`
