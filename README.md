# STTS751 package

ST STTS751 temperature Sensor I2C extension for makecode.  

Author: shaoziyang  
Date:   2019.Jul  

## Basic usage
```
basic.forever(function () {
    serial.writeValue("x", STTS751.temperature(STTS751.STTS751_T_UNIT.C))
    basic.pause(1000)
})
```


## License

MIT

Copyright (c) 2018, microbit/micropython Chinese community  

## Supported targets

* for PXT/microbit


[From microbit/micropython Chinese community](http://www.micropython.org.cn)
