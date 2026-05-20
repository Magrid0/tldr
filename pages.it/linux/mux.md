# mux

> Intercetta e multiplexa flussi di eventi di input.
> Maggiori informazioni: <https://gitlab.com/interception/linux/tools/-/tree/master#mux>.

- Crea un nuovo muxer con un nome specificato:

`mux -c {{muxer_name1 muxer_name2 ...}}`

- Imposta la dimensione della coda interna del muxer (predefinito è 100):

`mux -s {{size}}`

- Legge l'input da un muxer nominato (può essere ripetuto in "modalità switch"):

`mux -i {{input_muxer_name}}`

- Scrive l'output in un muxer nominato (può essere ripetuto):

`mux -o {{output_muxer_name}}`
