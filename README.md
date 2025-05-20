# Air quality station
V Electronics Air Quality Station design files & code, everything is open source and can be modified easily by the user. The device measures air pollution, temperature and humidity.

> [!NOTE]
> This is a work in progress!

# Specification:
Measurement range
| Air pollution | Temperature | Humidity |
| --------------- | --------------- | --------------- |
| todo | Item2.1   -40°C to +80°C ±0.5°C  | 0% to 99,9%RH ±3RH (at 25°C) |

- USB C power/programming (MCU fully unlocked)
- 2x16 LCD display + vertical bar LCD color display 
- No battery (a powerbank can be used)
- Not waterproof

# TODO
add test points
add drill holes to mount sensor to PCB
add gpio outputs for extra stuff
add led at analog output
add made in kicad (copy from cm5 io board)
wifi/bluetooth connectivity???

# Components list

- Seeed Studio XIAO ESP32C3 [link](https://wiki.seeedstudio.com/XIAO_ESP32C3_Getting_Started/)
<div style='text-align: center;'> 
<img src='https://files.seeedstudio.com/wiki/Seeeduino-XIAO/img/Seeeduino-XIAO-pinout-1.jpg' width='50%'>  
</div> 


> [!TODO] //find cheaper for example https://www.dfrobot.com/product-2526.html
- GRAVITY PM2.5 air quality sensor [link](https://www.dfrobot.com/product-2439.html)
<div style='text-align: center;'> 
<img src='https://cdn3.botland.store/img/art/inne/20678_16b.jpg' width='30%'>
</div> 
> [!NOTE]
> Other sensors can be used as alternatives if you need more precise measurements.


> [!TODO] //find suitable option
- LCD Display + I2C adapter [link]()
<div style='text-align: center;'> 
<img src='https://vishaworld.com/cdn/shop/products/0.96InchI2CIIC4pinOLEDDisplayModuleBLUE1.jpg?v=1624424421' width='30%'>  
</div> 


- Vertical bar vertical indicator [link](https://www.digikey.pl/en/products/detail/inolux/INBD-T11020-YGNB/16964097)
<div style='text-align: center;'> 
<img src='https://mm.digikey.com/Volume0/opasdata/d220001/derivates/6/003/226/366/INBD-T11020.YGNB_web%28640x640%29.jpg' width='30%'>  
</div> 


- AM2320 temperature & humidity sensor [link](https://www.digikey.pl/pl/products/detail/pimoroni-ltd/COM1700/8126047)
<div style='text-align: center;'> 
<img src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSvubqvIT2sCbDnZAM4_JZKVXFErDj4kKI99Q&s' width='30%'>  
</div> 
> [!NOTE]
> DHT12 can be used as a slightly cheaper alternative compromising accuracy and measurement range.


- On/Off switch [link](https://www.digikey.pl/en/products/detail/adam-tech/SW-T3-1A-A-A3-S1/15284460)
<div style='text-align: center;'> 
<img src='https://mm.digikey.com/Volume0/opasdata/d220001/medias/images/4428/MFG_SW-T3-1A-A-A3-S1.jpg' width='30%'>  
</div> 


- PS1240P02BT buzzer [link](https://www.digikey.pl/en/products/detail/tdk-corporation/PS1240P02BT/935924)
<div style='text-align: center;'> 
</div> 


- 2N3904 driving transistor [link](https://www.digikey.pl/en/products/detail/shenzhen-slkormicro-semicon-co-ltd/2N3904/26371060)
<div style='text-align: center;'> 
</div> 



