# fluidsynth

> Sintetizza audio da file MIDI.
> Maggiori informazioni: <https://github.com/FluidSynth/fluidsynth/wiki/UserManual>.

- Riproduce un file MIDI:

`fluidsynth {{/usr/share/soundfonts/soundfont.sf2}} {{path/to/file.midi}}`

- Specifica il driver audio:

`fluidsynth {{[-a|--audio-driver]}} {{pipewire|pulseaudio}} {{/usr/share/soundfonts/soundfont.sf2}} {{path/to/file.midi}}`

- Mostra aiuto:

`fluidsynth {{[-h|--help]}}`
