# koji cancel

> Annulla attività attive in esecuzione nel sistema di build Koji.
> Maggiori informazioni: <https://docs.pagure.org/koji/>.

- Annulla un'attività tramite il suo ID:

`koji cancel {{task_id}}`

- Annulla più attività:

`koji cancel {{task_id1 task_id2 ...}}`

- Annulla un'attività con output verboso:

`koji cancel --verbose {{task_id}}`

- Mostra aiuto:

`koji cancel {{[-h|--help]}}`
