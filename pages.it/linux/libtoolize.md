# libtoolize

> Uno strumento di `autotools` per preparare un pacchetto all'uso di `libtool`.
> Esegue vari compiti, inclusa la generazione di file e directory necessari per integrare `libtool` senza problemi in un progetto.
> Maggiori informazioni: <https://www.gnu.org/software/libtool/manual/libtool.html#Invoking-libtoolize>.

- Inizializza un progetto per `libtool` copiando i file necessari (evitando collegamenti simbolici) e sovrascrivendo i file esistenti se necessario:

`libtoolize {{[-cf|--copy --force]}}`
