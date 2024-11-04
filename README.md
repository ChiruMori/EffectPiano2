# Effect Piano V2

> 本项目 Fork 自 [Effect_Piano_light_controller](https://github.com/esun-z/Effect_Piano_light_controller)
> 原项目已不再活动，且存在 BUG。本项目对其进行了修复，并优化相关代码使其更可读可用。

## 说明

本项目用于控制 MIDI 键盘的外置灯光效果，通过 MIDI 键盘输入，控制 WS2812B 灯带的同步变化。

项目代码会在 Windows 的控制端和开发板上运行，需要以下设备：

- Arduino 开发板
- WS2812B 灯带
- MIDI 键盘（88键）
- Windows 设备

## 使用方法

[原项目帮助文档](https://www.bilibili.com/read/cv6327363)
  
## 工作原理

1. Windows 控制端读取 MIDI 输入设备的 MIDI 信号
2. Windows 控制端通过 USB 串口发送指定的信号到 Arduino 开发板
3. Arduino 开发板接受控制信号后控制 LED 的效果
