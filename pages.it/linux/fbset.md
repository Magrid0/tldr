# fbset

> Mostra e modifica le impostazioni del frame buffer.
> Maggiori informazioni: <https://manned.org/fbset.1>.

- Mostra le impostazioni correnti del framebuffer:

`sudo fbset {{[-i|--info]}}`

- Imposta una modalità del framebuffer definita in `/etc/fb.modes`:

`sudo fbset "{{800}}x{{600}}-{{60}}"`

- Imposta le dimensioni del framebuffer:

`sudo fbset -xres {{horizontal_pixels}} -yres {{vertical_pixels}}`

- Imposta una modalità arbitraria del framebuffer:

`sudo fbset {{[-g|--geometry]}} {{tty_horizontal}} {{tty_vertical}} {{monitor_horizontal}} {{monitor_vertical}} {{color_depth}}`
