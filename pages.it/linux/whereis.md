# whereis

> Trova i file binario, sorgente e di pagina di manuale per un comando.
> Vedi anche: `which`, `whatis`, `type`.
> Maggiori informazioni: <https://manned.org/whereis>.

- Trova binario, sorgente e pagine man per SSH:

`whereis {{ssh}}`

- Trova file [b]inari e pagine [m]an per ls:

`whereis -bm {{ls}}`

- Trova il [s]orgente di gcc e le pagine [m]an per Git:

`whereis -s {{gcc}} -m {{git}}`

- Trova [b]inari per gcc solo in `/usr/bin/`:

`whereis -b -B {{/usr/bin/}} -f {{gcc}}`

- Trova binari [i]nusuali (quelli che hanno più o meno di un binario sul sistema):

`whereis -u *`

- Trova binari che hanno voci di manuale [i]nusuali (binari che hanno più o meno di un manuale installato):

`whereis -u -m *`
