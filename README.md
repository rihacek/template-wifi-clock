##template-wall-clock

This template provides a lightweight foundation for future work. Many of my projects rely on wifi connections and time to provide time-series data to a central server, so consolidating those actions here is helpful.

- only output here is Serial
- change this info for your new project
- wifi enabled
- time pulled from NTP

###Note
I've included some info on configuring the ESP8266 WiFi chip in the comments. You can reset what's stored on the chip by changing board settings.

###Libraries:
- WifiManager - https://github.com/tzapu/WiFiManager
- NTPClient - https://github.com/arduino-libraries/NTPClient
