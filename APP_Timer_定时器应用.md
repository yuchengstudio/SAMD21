# 目录
## 概述

```
1.本实验使用SAMD21 Xplained pro开发板
2.使用start产生Timer驱动，并使用Timer定时器任务产生1s一次的LED闪烁功能。
```
demo板资料
http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42220-SAMD21-Xplained-Pro_User-Guide.pdf

最终项目工程
https://github.com/yuchengstudio/SAMD21/blob/master/reference_file/EDBG%20UART_SAMD21.rar

## SAMD21定时器应用概述
    Timer Driver应用说明
http://atmel-studio-doc.s3-website-us-east-1.amazonaws.com/webhelp/GUID-2A8AADED-413E-4021-AF0C-D99E61B8160D-en-US-2/index.html?GUID-E2199A86-03E7-4269-B532-372B3F8307D8
## 如何在start界面添加timer driver

## 使用start配置PIN口输出，点亮LED
 | 步骤 | 图示 | 说明 |
 | - | ---- | --- | 
 | 1 | ![images](https://github.com/yuchengstudio/SAMD21/blob/master/picture/SAMD21_Timer_001.jpg) | 找到SAM D21 Xplained Pro开发板中LED0对应芯片的Pin口脚 http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42220-SAMD21-Xplained-Pro_User-Guide.pdf| 
 | 2 | $1 | 6 | 
 | 3 | $1 | 7 |


## 如何添加应用代码调用驱动
