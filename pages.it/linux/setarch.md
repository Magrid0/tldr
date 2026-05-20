# setarch

> Cambia l'architettura riportata per l'esecuzione di un programma, usato principalmente per modificare come i programmi si comportano in base all'architettura di sistema.
> Utile per test di compatibilità o esecuzione di applicazioni legacy.
> Maggiori informazioni: <https://manned.org/setarch>.

- Esegue un comando come se l'architettura della macchina fosse `i686` (utile per eseguire app a 32 bit su un kernel a 64 bit):

`setarch i686 {{comando}}`

- Esegue una shell con l'architettura `x86_64`:

`setarch x86_64 {{bash}}`

- Disabilita la randomizzazione dello spazio degli indirizzi virtuali:

`setarch {{linux32}} {{[-R|--addr-no-randomize]}} {{comando}}`

- Elenca le architetture supportate:

`setarch --list`

- Mostra aiuto:

`setarch {{[-h|--help]}}`
