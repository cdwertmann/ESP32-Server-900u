- Works on ESP32S2 mini, but unstable on ESP32S3 zero
- Works with "esp32" v2.0.17 in Arduino Board Manager
- Have to reduce Wifi TX power, otherwise ESP32S2 crashes when connecting a Wifi client
- Must select 4MB SPIFFS partition scheme in Tools menu
- Board type is ESP32S2/3 Dev Module
- Upload goldhen.bin after flashing
- disable Psfree exploit because it often crashes the PS4 when loading goldhen

ESP32S3 zero crashes:
- when opening the settings page
- when WiFi.softAPConfig() is called
- when the exploit is running

Therefore use S2 for now.
