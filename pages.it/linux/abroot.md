# abroot

> Utility che fornisce completa immutabilità e atomicità tramite transizione tra 2 stati della partizione root (A⟺B).
> Gli aggiornamenti vengono eseguiti utilizzando immagini OCI, per garantire che il sistema sia sempre in uno stato consistente.
> Maggiori informazioni: <https://docs.vanillaos.org/docs/en/abroot-manpage>.

- Aggiunge pacchetti all'immagine locale (Nota: dopo aver eseguito questo comando, è necessario applicare queste modifiche.):

`sudo abroot pkg add {{pacchetto}}`

- Rimuove pacchetti dall'immagine locale (Nota: dopo aver eseguito questo comando, è necessario applicare queste modifiche.):

`sudo abroot pkg remove {{pacchetto}}`

- Elenca i pacchetti nell'immagine locale:

`sudo abroot pkg list`

- Applica le modifiche all'immagine locale (Nota: è necessario riavviare il sistema affinché le modifiche vengano applicate):

`sudo abroot pkg apply`

- Ripristina il sistema allo stato precedente:

`sudo abroot rollback`

- Modifica/Visualizza i parametri del kernel:

`sudo abroot kargs {{edit|show}}`

- Mostra lo stato:

`sudo abroot status`

- Mostra aiuto:

`abroot {{[-h|--help]}}`
