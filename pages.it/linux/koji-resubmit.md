# koji resubmit

> Riprova un'attività annullata o fallita, usando gli stessi parametri dell'attività originale.
> Maggiori informazioni: <https://docs.pagure.org/koji/>.

- Reinvia un'attività:

`koji resubmit {{task_id}}`

- Reinvia un'attività senza attendere il completamento:

`koji resubmit {{task_id}} --nowait`

- Reinvia un'attività senza stampare informazioni sull'attività:

`koji resubmit {{task_id}} --quiet`

- Mostra aiuto:

`koji resubmit {{[-h|--help]}}`
