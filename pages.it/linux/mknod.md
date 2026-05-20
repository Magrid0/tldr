# mknod

> Crea file speciali di dispositivo a blocchi o a caratteri.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/mknod-invocation.html>.

- Crea un dispositivo a blocchi:

`sudo mknod {{path/to/device_file}} b {{major_device_number}} {{minor_device_number}}`

- Crea un dispositivo a caratteri:

`sudo mknod {{path/to/device_file}} c {{major_device_number}} {{minor_device_number}}`

- Crea un dispositivo FIFO (coda):

`sudo mknod {{path/to/device_file}} p`

- Crea un file di dispositivo con contesto di sicurezza SELinux predefinito:

`sudo mknod {{[-Z|--context]}} {{path/to/device_file}} {{type}} {{major_device_number}} {{minor_device_number}}`
