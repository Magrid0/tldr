# sinfo

> Visualizza informazioni sui nodi e le partizioni Slurm.
> Vedi anche: `squeue`, `sbatch`.
> Maggiori informazioni: <https://slurm.schedmd.com/sinfo.html>.

- Mostra una rapida panoramica del cluster:

`sinfo {{[-s|--summarize]}}`

- Visualizza lo stato dettagliato di tutte le partizioni nell'intero cluster:

`sinfo`

- Visualizza lo stato dettagliato di una partizione specifica:

`sinfo {{[-p|--partition]}} {{nome_partizione}}`

- Visualizza informazioni sui nodi inattivi:

`sinfo {{[-t|--states]}} {{idle}}`

- Riassume i nodi morti:

`sinfo {{[-d|--dead]}}`

- Elenca i nodi morti e le relative ragioni:

`sinfo {{[-R|--list-reasons]}}`
