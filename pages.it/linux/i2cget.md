# i2cget

> Legge da un registro di un dispositivo I2C.
> Vedi anche: `i2cdetect`, `i2cdump`, `i2cset`.
> Nota: tutti gli indirizzi devono essere specificati in esadecimale.
> Maggiori informazioni: <https://manned.org/i2cget>.

- Legge da un registro di un dispositivo I2C:

`i2cget {{i2cbus}} {{device_address}} {{register_address}}`

- Legge da un registro di un dispositivo I2C senza chiedere conferma:

`i2cget -y {{i2cbus}} {{device_address}} {{register_address}}`

- Legge da un registro di un dispositivo I2C usando una modalità specifica:

`i2cget {{i2cbus}} {{device_address}} {{register_address}} {{b|w|c|s|i}}`
