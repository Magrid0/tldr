# virt-xml-validate

> Convalida i file XML di `libvirt` contro uno schema.
> Se non viene specificato uno schema, lo schema viene determinato dall'elemento radice nel file XML.
> Maggiori informazioni: <https://libvirt.org/manpages/virt-xml-validate.html>.

- Convalida un file XML contro uno schema specifico:

`virt-xml-validate {{percorso/del/file.xml}} {{schema}}`

- Convalida il dominio XML contro lo schema del dominio:

`virt-xml-validate {{percorso/del/dominio.xml}} domain`
