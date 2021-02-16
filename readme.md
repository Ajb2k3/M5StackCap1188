#**Adadfruit Cap1188 on M5Stack.**

```i2c0 = i2c_bus.easyI2C(i2c_bus.PORTA, 0x29, freq=400000)``` CAP1188 connected to Port A.

##Registers

Write Register ``` (0x72, 0xff) ``` Led link register 0x00 = all off, 0xff = all light when analog pins detect contact.
Read Register ``` (0x02) ``` Holds the LED status.
Read/Write register``` (0x00, 0x01) ``` Main Power Control register
  
  ##Analog pins
 ``` (i2c0.read_u8(0x10)```
 ``` (i2c0.read_u8(0x11)```
 ``` (i2c0.read_u8(0x12)```
```  (i2c0.read_u8(0x13)```
```  (i2c0.read_u8(0x14)```
```  (i2c0.read_u8(0x15)```
```  (i2c0.read_u8(0x16)```
```  (i2c0.read_u8(0x17)```
