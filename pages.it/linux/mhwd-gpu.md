# mhwd-gpu

> Configura le schede grafiche in Manjaro.
> Maggiori informazioni: <https://wiki.manjaro.org/index.php/Configure_NVIDIA_(non-free)_settings_and_load_them_on_Startup/en#Configure_The_Resolution.2FRefresh_Rate>.

- Mostra il percorso corrente della configurazione Xorg:

`mhwd-gpu --status`

- Controlla se la configurazione Xorg ha un collegamento simbolico valido:

`mhwd-gpu --check`

- Imposta una configurazione Xorg personalizzata per una GPU NVIDIA:

`sudo mhwd-gpu --setmod nvidia --setxorg /{{path/to/nvidia.conf}}`

- Imposta una configurazione Xorg personalizzata per una GPU AMD:

`sudo mhwd-gpu --setmod {{catalyst|ati}} --setxorg /{{path/to/amdgpu.conf}}`

- Mostra aiuto:

`mhwd-gpu --help`
