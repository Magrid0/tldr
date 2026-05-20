# secon

> Ottiene il contesto di sicurezza SELinux di un file, pid, contesto di esecuzione corrente o una specifica di contesto.
> Vedi anche: `semanage`, `runcon`, `chcon`.
> Maggiori informazioni: <https://manned.org/secon>.

- Ottiene il contesto di sicurezza del contesto di esecuzione corrente:

`secon`

- Ottiene il contesto di sicurezza corrente di un processo:

`secon --pid {{1}}`

- Ottiene il contesto di sicurezza corrente di un file, risolvendo tutti i collegamenti simbolici intermedi:

`secon --file {{percorso/del/file_o_directory}}`

- Ottiene il contesto di sicurezza corrente di un collegamento simbolico stesso (cioè non risolvere):

`secon --link {{percorso/del/collegamento_simbolico}}`

- Analizza e spiega una specifica di contesto:

`secon {{system_u:system_r:container_t:s0:c899,c900}}`
