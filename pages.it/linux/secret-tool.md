# secret-tool

> Memorizza e recupera password, parte del pacchetto `libsecret`.
> Comunica con le implementazioni del servizio di segreti Freedesktop come `gnome-keyring`.
> Maggiori informazioni: <https://gnome.pages.gitlab.gnome.org/libsecret/>.

- Memorizza un segreto con un'etichetta opzionale:

`secret-tool store --label={{etichetta}} {{chiave}} {{valore}}`

- Recupera un segreto:

`secret-tool lookup key {{chiave}}`

- Ottiene più informazioni su un segreto:

`secret-tool search key {{chiave}}`

- Elimina un segreto memorizzato:

`secret-tool clear key {{chiave}}`
