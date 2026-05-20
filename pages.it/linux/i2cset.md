# i2cset

> Imposta il valore di un registro di un dispositivo I2C.
> Vedi anche: `i2cdetect`, `i2cdump`, `i2cget`.
> Nota: tutti gli indirizzi devono essere specificati in esadecimale.
> Maggiori informazioni: <https://manned.org/i2cset>.

- Scrivi in un registro di un dispositivo I2C:

`i2cset {{i2cbus}} {{device_address}} {{register_address}} {{value}}`

- Scrivi in un registro di un dispositivo I2C senza chiedere conferma:

`i2cset -y {{i2cbus}} {{device_address}} {{register_address}} {{value}}`

- Scrivi in un registro di un dispositivo I2C usando una modalità specifica:

`i2cset {{i2cbus}} {{device_address}} {{register_address}} {{value}} {{b|w|c|s|i}}`
