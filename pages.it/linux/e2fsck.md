# e2fsck

> Controlla un filesystem Linux ext2/ext3/ext4. La partizione dovrebbe essere smontata.
> Maggiori informazioni: <https://manned.org/e2fsck>.

- Controlla il filesystem, segnalando eventuali blocchi danneggiati:

`sudo e2fsck {{/dev/sdXN}}`

- Controlla il filesystem e ripara automaticamente ([p]reen) eventuali blocchi danneggiati:

`sudo e2fsck -p {{/dev/sdXN}}`

- Controlla il filesystem in modalità sola lettura:

`sudo e2fsck -c {{/dev/sdXN}}`

- [f]orza il controllo anche se il filesystem sembra pulito:

`sudo e2fsck -f {{/dev/sdXN}}`

- Esegue un test esaustivo non distruttivo di lettura-scrittura per blocchi danneggiati e li inserisce nella lista nera:

`sudo e2fsck -fccky {{/dev/sdXN}}`
