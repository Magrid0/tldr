# systemd-ac-power

> Segnala se il computer è collegato a una fonte di alimentazione esterna.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-ac-power.html>.

- Controlla silenziosamente e restituisce un codice di stato 0 quando è alimentato a corrente, e un codice diverso da zero altrimenti:

`systemd-ac-power`

- Inoltre stampa `yes` o `no` su `stdout`:

`systemd-ac-power {{[-v|--verbose]}}`
