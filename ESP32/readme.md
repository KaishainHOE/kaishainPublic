### ESP32 tools
- ESP-IDF tools
-ESP-PORG 設定
[web links ESP-IDF tools](https://docs.espressif.com/projects/esp-idf/zh_CN/latest/esp32/api-guides/jtag-debugging/configure-ft2232h-jtag.html#usb)

### ESP32C3 pin define

[ESP32 C3](https://forum.arduino.cc/t/esp32-c3-supermini-pinout/1189850)


### ESP32C# program
- I had the same issue. After many tries the solution was pretty easy :
1. Press BOOT button and keep pressed,
2. Press briefly RST button,
3. Release BOOT button.
- This puts the board in download mode again.
- I found both "ESP3C3 Dev Module" and "LOLIN C3 Mini" to work with this board.
- [link](https://forum.arduino.cc/t/esp32-c3-super-mini-cant-upload-any-sketch/1229072/23?_gl=1*ahvf4t*_up*MQ..*_ga*MTg0MDc0MjE0NC4xNzM2NzgzODg1*_ga_NEXN8H46L5*MTczNjc4Mzg4Mi4xLjEuMTczNjc4MzkwMS4wLjAuMTkyNjI2NTk4)