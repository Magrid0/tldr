# restorecon

> Ripristina il contesto di sicurezza SELinux su file/directory secondo regole persistenti.
> Vedi anche: `semanage-fcontext`.
> Maggiori informazioni: <https://manned.org/restorecon>.

- Visualizza il contesto di sicurezza corrente di un file o directory:

`ls {{[-dlZ|--directory -l --context]}} {{path/to/file_or_directory}}`

- Ripristina il contesto di sicurezza di un file o directory:

`restorecon {{path/to/file_or_directory}}`

- Ripristina il contesto di sicurezza di una directory in modo ricorsivo e mostra tutte le etichette cambiate:

`restorecon -R -v {{path/to/directory}}`

- Ripristina il contesto di sicurezza di una directory in modo ricorsivo, usando tutti i thread disponibili e mostra il progresso:

`restorecon -R -T {{0}} -p {{path/to/directory}}`

- Mostra in anteprima le modifiche alle etichette che avverrebbero senza applicarle:

`restorecon -R -n -v {{path/to/directory}}`
