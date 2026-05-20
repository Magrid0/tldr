# bpftool

> Ispeziona e manipola programmi e mappe eBPF in modo semplice.
> Alcuni sottocomandi come `prog` hanno la propria documentazione d'uso.
> Maggiori informazioni: <https://manned.org/bpftool>.

- Elenca informazioni sui programmi `eBPF` caricati:

`bpftool prog list`

- Elenca gli attaccamenti dei programmi `eBPF` nel sottosistema di rete del kernel:

`bpftool net list`

- Elenca tutti i link attivi:

`bpftool link list`

- Elenca tutti gli attaccamenti `raw_tracepoint`, `tracepoint`, `kprobe` nel sistema:

`bpftool perf list`

- Elenca i dati `BPF Type Format (BTF)`:

`bpftool btf list`

- Elenca informazioni sulle mappe caricate:

`bpftool map list`

- Sonda un dispositivo di rete "eth0" per le funzionalità `eBPF` supportate:

`bpftool feature probe dev {{eth0}}`

- Esegue comandi in modalità batch da un file:

`bpftool batch file {{myfile}}`
