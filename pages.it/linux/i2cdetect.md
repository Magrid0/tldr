# i2cdetect

> Scansiona i bus I2C.
> Vedi anche: `i2cdump`, `i2cget`, `i2cset`.
> Maggiori informazioni: <https://manned.org/i2cdetect>.

- Elenca i bus I2C attivi:

`i2cdetect -l`

- Scansiona i dispositivi su un bus I2C:

`i2cdetect {{i2c_bus}}`

- Scansiona i dispositivi su un bus I2C senza chiedere conferma:

`i2cdetect -y {{i2c_bus}}`
