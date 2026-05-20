# amdgpu_top

> Strumento per mostrare l'utilizzo della GPU AMD e le metriche hardware utilizzando il driver AMDGPU.
> Vedi anche: `nvtop`, `radeontop`.
> Maggiori informazioni: <https://github.com/Umio-Yasuno/amdgpu_top#usage>.

- Mostra un elenco di dispositivi AMDGPU:

`amdgpu_top --list`

- Scarica tutti i processi GPU e l'utilizzo della memoria per processo:

`amdgpu_top {{[-p|--process]}}`

- Seleziona una GPU specifica tramite bus PCI:

`amdgpu_top --pci "{{0000:01:00.0}}"`

- Avvia il monitor interattivo TUI:

`amdgpu_top`

- Avvia il monitor GUI:

`amdgpu_top --gui`

- Avvia una semplice vista TUI simile a SMI:

`amdgpu_top --smi`
