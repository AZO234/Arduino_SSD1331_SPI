Library of Color OLED modules connect with SSD1331(SPI bus) by AZO
==================================================================
version: v1.0.1(Sep 19, 2019)  
http://domisan.sakura.ne.jp/

Library of Color OLED modules connect with SSD1331(SPI bus).

Connect Arduino UNO as follow.

3.3V - VDD  
 GND - GND  
  13 - SCK  
  11 - SDA  
   9 - RES  
   8 - DC  
  10 - CS

First constrast instance of class SSD1331_SPI.  
Next call Initialize(); and initDevice();  
Then draw with DrawPixel();

Reference
---------
- SSD1331 Advance Information
https://cdn-shop.adafruit.com/datasheets/SSD1331_1.2.pdf
- フルカラー OLED SSD1331 を ESP32 ( ESP-WROOM-32 )で動かしてみた | mgo-tec電子工作  
https://www.mgo-tec.com/blog-entry-esp32-oled-ssd1331.html
- 円を描く (1)円弧描画のアルゴリズム
http://fussy.web.fc2.com/algo/algo2-1.htm

