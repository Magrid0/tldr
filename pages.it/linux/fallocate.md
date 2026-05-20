# fallocate

> Riserva o dealloca spazio su disco per i file.
> L'utility alloca spazio senza azzerarlo.
> Maggiori informazioni: <https://manned.org/fallocate>.

- Riserva un file occupante 700 MiB di spazio su disco:

`fallocate {{[-l|--length]}} 700M {{path/to/file}}`

- Riduce un file già allocato di 200 MB:

`fallocate {{[-c|--collapse-range]}} {{[-l|--length]}} 200MB {{path/to/file}}`

- Riduce 20 MB di spazio dopo 100 MiB in un file:

`fallocate {{[-c|--collapse-range]}} {{[-o|--offset]}} 100M {{[-l|--length]}} 20M {{path/to/file}}`
