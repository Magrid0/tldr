# bluebuild

> Crea Containerfile e immagini personalizzate basate su `recipe.yml`.
> Maggiori informazioni: <https://github.com/blue-build/cli#how-to-use>.

- Crea una ricetta:

`bluebuild build {{path/to/recipe.yml}}`

- Convalida una ricetta:

`bluebuild validate {{path/to/recipe.yml}}`

- Genera un Containerfile:

`bluebuild generate {{[-o|--output]}} {{Containerfile}} {{path/to/recipe.yml}}`

- Genera un ISO da una ricetta:

`bluebuild generate-iso --output-dir {{path/to/output_directory}} --iso-name {{iso_name.iso}} recipe {{path/to/recipe.yml}}`

- Mostra aiuto:

`bluebuild {{[-h|--help]}}`
