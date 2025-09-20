# AIOT-Project

概述：基于ESP32S2模组(https://www.digikey.cn/zh/products/detail/espressif-systems/ESP32-S2-MINI-2-N4R2/16591895)设计了一款家用的远程I/O控制板。在这块控制板上，包含了8路继电器输出，4路光耦隔离输入，一个SHT30温湿度传感器(https://www.digikey.cn/zh/products/detail/sensirion-ag/SHT30-DIS-B2-5KS/5872250 )，一个KDT00030光感传感器(https://www.digikey.cn/zh/products/detail/onsemi/KDT00030ATR/4562744 )，可以用这块控制器实现家电控制，温湿度监测，环境光监测以及其他数字传感器输入。

板卡的固件使用ESPHOME进行设计，ESPHome 是一个专为 ESP8266 和 ESP32 微控制器设计的开源框架，可以简化智能家居设备的开发与配置。它通过简单的 YAML 配置文件实现设备功能的定义，无需深入底层编程，降低了物联网项目的门槛。
