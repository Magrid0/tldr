# ico

> Mostra un'animazione di un poliedro.
> Maggiori informazioni: <https://manned.org/ico>.

- Mostra il wireframe di un icosaedro che cambia posizione ogni 0.1 secondi:

`ico -sleep {{0.1}}`

- Mostra un icosaedro solido con facce rosse su sfondo blu:

`ico -faces -noedges -colors {{red}} -bg {{blue}}`

- Mostra il wireframe di un cubo di dimensione 100x100 che si muove di +1+2 per fotogramma:

`ico -obj {{cube}} -size {{100x100}} -delta {{+1+2}}`

- Mostra il wireframe invertito di un icosaedro con larghezza linea 10 usando 5 thread:

`ico -i -lw {{10}} -threads {{5}}`
