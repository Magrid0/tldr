# rpmbuild

> Strumento di creazione pacchetti RPM.
> Maggiori informazioni: <https://manned.org/rpmbuild>.

- Crea pacchetti binari e sorgente:

`rpmbuild -ba {{path/to/spec_file}}`

- Crea un pacchetto binario senza pacchetto sorgente:

`rpmbuild -bb {{path/to/spec_file}}`

- Specifica variabili aggiuntive durante la creazione di un pacchetto:

`rpmbuild -bb {{path/to/spec_file}} --define "{{variable1}} {{value1}}" --define "{{variable2}} {{value2}}"`
