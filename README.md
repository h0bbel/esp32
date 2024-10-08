# ESP32 Code

## 1. [ESP-WIFI-RICKROLLER](esp-wifi-rickroller/esp-wifi-rickroller.ino)

Runs a WiFi access point that changes its SSID every 30s. The SSID names are based on the lyrics of "Never Gonna Give You Up" by Rick Astley.

Anyone connecting to it, will be shown a captive portal and the connection will be logged on the ESP32 via SPIFFS. No client details are logged, only that a connection was made and a timestamp based on milliseconds since the ESP32 was powered on.

Based on [esp-wifi-rickroller](https://github.com/marcelstoer/esp-wifi-rickroller) but enhanced with logging and an admin page to view/reset logs.

Tested on *ESP32-WROOM-32U*.
