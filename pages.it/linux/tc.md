# tc

> Mostra/modifica le impostazioni di controllo del traffico.
> Maggiori informazioni: <https://manned.org/tc>.

- Aggiungi un ritardo di rete costante ai pacchetti in uscita:

`sudo tc {{[q|qdisc]}} {{[a|add]}} dev {{eth0}} root netem delay {{ritardo_in_millisecondi}}ms`

- Aggiungi un ritardo di rete distribuito normalmente ai pacchetti in uscita:

`sudo tc {{[q|qdisc]}} {{[a|add]}} dev {{eth0}} root netem delay {{ritardo_medio_ms}}ms {{deviazione_std_ms}}ms`

- Aggiungi corruzione/perdita/duplicazione di pacchetti a una parte dei pacchetti:

`sudo tc {{[q|qdisc]}} {{[a|add]}} dev {{eth0}} root netem {{corruption|loss|duplication}} {{percentuale_effetto}}%`

- Limita la larghezza di banda, il tasso di burst e la latenza massima:

`sudo tc {{[q|qdisc]}} {{[a|add]}} dev eth0 root tbf rate {{larghezza_banda_max_mb}}mbit burst {{tasso_burst_max_kb}}kbit latency {{latenza_max_prima_di_scarto_ms}}ms`

- Mostra le politiche di controllo del traffico attive:

`tc {{[q|qdisc]}} {{[s|show]}} dev {{eth0}}`

- Elimina tutte le regole di controllo del traffico:

`sudo tc {{[q|qdisc]}} {{[d|delete]}} dev {{eth0}}`

- Modifica una regola di controllo del traffico:

`sudo tc {{[q|qdisc]}} {{[c|change]}} dev {{eth0}} root netem {{politica}} {{parametri_politica}}`
