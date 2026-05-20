# rusnapshot

> Utilità di snapshot BTRFS scritta in Rust.
> Maggiori informazioni: <https://github.com/Edu4rdSHL/rusnapshot>.

- Crea uno snapshot usando un file di configurazione:

`sudo rusnapshot {{[-c|--config]}} {{path/to/config.toml}} --cr`

- Elenca gli snapshot creati:

`sudo rusnapshot {{[-c|--config]}} {{path/to/config.toml}} {{[-l|--list]}}`

- Elimina uno snapshot tramite ID o nome dello snapshot:

`sudo rusnapshot {{[-c|--config]}} {{path/to/config.toml}} --del --id {{snapshot_id}}`

- Elimina tutti gli snapshot `hourly`:

`sudo rusnapshot {{[-c|--config]}} {{path/to/config.toml}} {{[-l|--list]}} {{[-k|--keep]}} {{0}} --clean --kind {{hourly}}`

- Crea uno snapshot in lettura-scrittura:

`sudo rusnapshot {{[-c|--config]}} {{path/to/config.toml}} --cr {{[-r|--rw]}}`

- Ripristina uno snapshot:

`sudo rusnapshot {{[-c|--config]}} {{path/to/config.toml}} --id {{snapshot_id}} {{[-r|--restore]}}`
