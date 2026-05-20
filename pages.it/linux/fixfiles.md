# fixfiles

> Corregge i contesti di sicurezza SELinux dei file.
> Maggiori informazioni: <https://manned.org/fixfiles>.

- Se specificato con onboot, fixfiles registra la data corrente nel file `/.autorelabel`, in modo da poter essere utilizzata successivamente per velocizzare l'etichettatura. Se utilizzato con restore, il ripristino interesserà solo i file modificati oggi:

`fixfiles -B`

- [F]orza il ripristino del contesto per corrispondere a `file_context` per i file personalizzabili:

`fixfiles -F`

- Pulisce la directory `/tmp` senza conferma:

`fixfiles -f`

- Utilizza il database [R]pm per scoprire tutti i file all'interno di pacchetti specifici e ripristina i contesti dei file:

`fixfiles -R {{rpm_package1,rpm_package2 ...}}`

- Esegue un diff sul file `PREVIOUS_FILECONTEXT` rispetto a quello [C]orrentemente installato e ripristina il contesto di tutti i file interessati:

`fixfiles -C PREVIOUS_FILECONTEXT`

- Agisce solo sui file creati dopo una data specifica, che verrà passata al comando find `--newermt`:

`fixfiles -N {{YYYY-MM-DD HH:MM}}`

- [M]onta i filesystem prima di rietichettarli, consentendo di correggere il contesto di file o directory che sono stati montati sopra:

`fixfiles -M`

- Modifica la [v]erbosità da progress a verbose ed esegue `restorecon` con `-v` invece di `-p`:

`fixfiles -v`
