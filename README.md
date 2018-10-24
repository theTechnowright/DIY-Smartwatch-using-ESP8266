# DIY-Smartwatch-using-ESP8266
This is an ESP8266 project in which I make a smartwatch that connects to the internet and gets the time data from NTP and gets the weather data from Yahoo Weather API. The data is displayed on an OLED display mounted to a PCB. Besides this the button present on the watch can control another ESP8266 Relay module directly through an IoT cloud service called Blynk.
Make sure to download and install the following arduino libraries:
  Time.h & TimeLib.h:  https://github.com/PaulStoffregen/Time
  Timezone.h: https://github.com/JChristensen/Timezone
  SSD1306.h & SSD1306Wire.h:  https://github.com/squix78/esp8266-oled-ssd1306
  NTPClient.h: https://github.com/arduino-libraries/NTPClient
  ESP8266WiFi.h & WifiUDP.h: https://github.com/ekstrand/ESP8266wifi

  Download latest Blynk library here: https://github.com/blynkkk/blynk-library/releases/latest
