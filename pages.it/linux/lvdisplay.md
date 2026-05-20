# lvdisplay

> Mostra informazioni sui volumi logici di Logical Volume Manager (LVM).
> Vedi anche: `lvm`, `lvs`.
> Maggiori informazioni: <https://manned.org/lvdisplay>.

- Mostra informazioni su tutti i volumi logici:

`sudo lvdisplay`

- Mostra le informazioni in formato breve (come eseguire `lvs`):

`sudo lvdisplay {{[-C|--columns]}}`

- Mostra informazioni su tutti i volumi logici nel gruppo di volumi vg1:

`sudo lvdisplay {{vg1}}`

- Mostra informazioni sul volume logico lv1 nel gruppo di volumi vg1:

`sudo lvdisplay {{vg1/lv1}}`
