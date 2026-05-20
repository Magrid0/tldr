# legit

> Interfaccia a riga di comando complementare per Git.
> Maggiori informazioni: <https://frostming.github.io/legit/>.

- Passa a un ramo specificato, salvando temporaneamente e ripristinando le modifiche non staged:

`git sw {{target_branch}}`

- Sincronizza il ramo corrente, unendo o riorganizzando automaticamente, e salvando temporaneamente e ripristinando:

`git sync`

- Pubblica un ramo specificato sul server remoto:

`git publish {{branch_name}}`

- Rimuove un ramo dal server remoto:

`git unpublish {{branch_name}}`

- Elenca tutti i rami e il loro stato di pubblicazione:

`git branches {{glob_pattern}}`

- Rimuove l'ultimo commit dalla cronologia:

`git undo --hard`
