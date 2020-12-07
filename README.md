# YEF2020
YEF 2020 ESP8266 Code

Useful links:
Aruduino Studio download - https://www.arduino.cc/en/software
ESP8266 pin out - https://randomnerdtutorials.com/esp8266-pinout-reference-gpios/
Library for OLED screen - https://github.com/adafruit/Adafruit_SSD1306

Pin out as used for your YEF box:
OLED Screen to ESP8266:
VCC -> 3V on ESP8266
GND -> G on ESP8266
SCL -> D1 on ESP8266
SDA -> D2 on ESP8266

Buzzer:
Positive side (long pin) - D5 on ESP8266
Negative side (short pin) - G on ESP8266

If you are not powering the ESP8266 via a battery, you can power it from the micro usb port.

If you are powering the ESP8266 via a battery, please connect positive side of the battery to "VIN" on the ESP8266 and the negative side of the battery to "G" on the ESP8266. 

Remember, google is your friend when it comes to anything IOT :) 
