# ESP-Box-Bridge

[![Build Status](https://github.com/stops-top/usb-bridge-esp/workflows/ci/badge.svg)](https://github.com/stops-top/usb-bridge-esp/actions/workflows/ci.yml)


基于BOX开发的烧录和测试工具

在原工程的基础上，添加设备管理功能，主要是识别到具体的ESP32芯片型号，然后管理相应芯片，在烧录过程中识别对象并选择

| IO配置 | Camera | LCD | NFC | MIC/Speaker | BTN | Touch | LED | SD | DET | Finger |
| ----- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| Type | USB | SPI |  | I2S/I2C/IO  | IO | IO | IO | SDIO | ADC | UART |
| GPIO  | 40 | 41 | 38 | 39 | 42 | 21 | 10 | 9 | 43 | 11 |


目前还没有完全适配v5.0版本
