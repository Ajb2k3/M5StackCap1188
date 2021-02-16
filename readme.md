**Adadfruit Cap1188 on M5Stack.**

```i2c0 = i2c_bus.easyI2C(i2c_bus.PORTA, 0x29, freq=400000)```
CAP1188 connected to Port A.

Registers

 ``` i2c0.write_u8(0x72, 0xff) ```
 ``` i2c0.write_u8(0x02, 0x00) ```
 ``` i2c0.write_u8(0x00, 0x01) ```
  
  Analog pins
 ``` (i2c0.read_u8(0x10)```
 ``` (i2c0.read_u8(0x11)```
 ``` (i2c0.read_u8(0x12)```
```  (i2c0.read_u8(0x13)```
```  (i2c0.read_u8(0x14)```
```  (i2c0.read_u8(0x15)```
```  (i2c0.read_u8(0x16)```
```  (i2c0.read_u8(0x17)```
