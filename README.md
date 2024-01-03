# Smartphone based on ESP32 S3

Smartphone based on esp32s3 with GSM, WIFI, Bluetooth and more functions.

## TODO

- [x] UI
- [ ] WiFi
- [ ] Bluetooth
- [ ] SIM
- [ ] Calls & SMS
- [ ] Portable Hotspot
- [ ] OTA

## Used Tools

- VSCode + PlatformIO
- LVGL
- FreeRTOS
- Arduino Framework
- GUI Editors

## Hardware

- [Display ST7796 + XPT2046](http://www.lcdwiki.com/4.0inch_SPI_Module_ST7796)
- [ESP32S3](https://www.waveshare.com/esp32-s3-pico.htm)

## Specs

| ESP32S3 | Info   |
| ------- | ------ |
| f_size  | 16Mb   |
| f_cpu   | 240MHz |
| f_flash | 80Mhz  |

## Connections

| TFT PINS     | ESP32S3 |
| ------------ | ------- |
| TFT_MISO     | 13      |
| TFT_MOSI     | 11      |
| TFT_SCLK     | 12      |
| TFT_CS       | 8       |
| TFT_DC       | 14      |
| TFT_TOUCH_CS | 15      |

## Flashing bin files

- With [esptool-js](https://espressif.github.io/esptool-js/) you can flash ESP32 via web.

    | Location | File               |
    | -------- | ------------------ |
    | 0x0000   | bin/bootloader.bin |
    | 0x8000   | bin/partitions.bin |
    | 0xe000   | bin/boot_app0.bin  |
    | 0x10000  | bin/firmware.bin   |

## Video

![gif](https://imgur.com/BoUJO6y.gif)

![gif](https://imgur.com/wojd5uF.gif)

## ScreenShots

![home](https://imgur.com/MNnYTZh.png)

![phone](https://imgur.com/B81hUai.png)

![settings](https://imgur.com/fsxie5i.png)

![messages](https://imgur.com/DU3u41j.png)

[![Donate with PayPal](https://raw.githubusercontent.com/stefan-niedermann/paypal-donate-button/master/paypal-donate-button.png)](https://www.paypal.me/ajay8866)

## Disclaimer

- This project it's just for hobby project. Design is inspired by iOS.

## Important

- Use this project at your own risc.

<!-- https://imgur.com/a/c68v3SE -->