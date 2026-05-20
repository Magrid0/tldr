# zramctl

> Configura e controlla i dispositivi zram.
> Usa `mkfs` o `mkswap` per formattare i dispositivi zram in partizioni.
> Maggiori informazioni: <https://manned.org/zramctl>.

- Verifica se zram è abilitato:

`lsmod | grep {{[-i|--ignore-case]}} zram`

- Abilita zram con un numero dinamico di dispositivi (usa `zramctl` per configurare ulteriormente i dispositivi):

`sudo modprobe zram`

- Abilita zram con esattamente 2 dispositivi:

`sudo modprobe zram num_devices={{2}}`

- Trova e inizializza il prossimo dispositivo zram libero come unità virtuale da 2 GB usando compressione LZ4:

`sudo zramctl {{[-f|--find]}} {{[-s|--size]}} {{2GB}} {{[-a|--algorithm]}} {{lz4}}`

- Elenca i dispositivi attualmente inizializzati:

`sudo zramctl`
