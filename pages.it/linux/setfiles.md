# setfiles

> Imposta i contesti di sicurezza dei file SELinux in base alle regole delle politiche.
> Simile a `restorecon` ma legge i contesti da un file file_contexts.
> Vedi anche: `restorecon`, `semanage-fcontext`, `fixfiles`.
> Maggiori informazioni: <https://manned.org/setfiles>.

- Imposta i contesti dei file secondo il file di politica predefinito:

`sudo setfiles /etc/selinux/targeted/contexts/files/file_contexts {{percorso/della/directory}}`

- Imposta i contesti dei file ricorsivamente e mostra le modifiche:

`sudo setfiles /etc/selinux/targeted/contexts/files/file_contexts {{percorso/della/directory}} {{[-v|--verbose]}}`

- Mostra un'anteprima di ciò che verrebbe modificato senza effettivamente modificare i contesti:

`sudo setfiles /etc/selinux/targeted/contexts/files/file_contexts {{percorso/della/directory}} {{[-n|--nochange]}}`

- Imposta i contesti dei file e li verifica:

`sudo setfiles /etc/selinux/targeted/contexts/files/file_contexts {{percorso/della/directory}} {{[-v|--verbose]}} {{[-F|--force]}}`

- Usa un percorso root specifico per la corrispondenza dei contesti:

`sudo setfiles /etc/selinux/targeted/contexts/files/file_contexts {{percorso/della/nuova_directory}} {{[-r|--rootpath]}} {{percorso/della/vecchia_directory}}`
