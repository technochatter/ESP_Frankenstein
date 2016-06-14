# ESP_Frankenstein
####Added more pins to my ESP8266_01 board with careful soldering & skills ;)
Used enameled wire from defunct earphone headset wires, scraped off the end to solder and added a lot of flux to increase surface tension before soldering.Then closed my eyes during soldering and hoped for the best.
##Pictures:
![soldering pins](https://raw.githubusercontent.com/technochatter/ESP_Frankenstein/master/pics/IMG_5099.JPG?raw=true)
![image](https://github.com/technochatter/ESP_Frankenstein/blob/master/pics/IMG_5101.JPG?raw=true)
![image](https://github.com/technochatter/ESP_Frankenstein/blob/master/pics/IMG_5108.JPG?raw=true)
![image](https://github.com/technochatter/ESP_Frankenstein/blob/master/pics/IMG_5111.JPG?raw=true)
![image](https://github.com/technochatter/ESP_Frankenstein/blob/master/pics/IMG_5112.JPG?raw=true)
![image](https://github.com/technochatter/ESP_Frankenstein/blob/master/pics/IMG_5114.JPG?raw=true)
![image](https://github.com/technochatter/ESP_Frankenstein/blob/master/pics/IMG_5118.JPG?raw=true)
![image](https://github.com/technochatter/ESP_Frankenstein/blob/master/pics/IMG_5123.JPG?raw=true)
##Important Pins available:
IC Pin No | Functional Name | Special Use
-------|-------|--------------
6|TOUT|Acts as ADC input(Need to float when measure supply voltage)
7|CH_EN|Chip Enable when tied to High(*Present in ESP_01*)
8|GPIO16| Deep Sleep WakeUp(Need to be connected to Reset pin)
9|GPIO14|(I2C_SCL)HSPI_CLK
10|GPIO12|HSPI_MISO
14|GPIO2|Indicates Flash Mode Acive(*Present in ESP_01*)
15|GPIO0|Activates Flash Mode when tied to GND(*Present in ESP_01*)
16|GPIO4|Normal GPIO
25|U0RXD|RX During Flash Prog or Serial Comm.(*Present in ESP_01*)
26|U0TXD|TX During Flash Prog or Serial Comm.(*Present in ESP_01*)
32|EXT_RSTB|Reset Pin(*Present in ESP_01*)




##Project List:
https://github.com/technochatter/LM35speak
