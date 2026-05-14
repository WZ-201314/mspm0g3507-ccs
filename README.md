 TI-MSPM0G3507-code

 项目概述

本仓库收集了基于 TI MSPM0G3507 MCU 的示例工程代码，使用 Texas Instruments Code Composer Studio (CCS) 开发。仓库中的示例主要展示了 MSPM0G3507 的外设驱动、定时器、ADC、UART、PWM、DMA、FFT 等常见功能。

 目录结构

- `01_led/` - LED 控制示例
- `02_key/` - 按键输入示例
- `03_oled/` - OLED 显示示例
- `04_TIM/` - 定时器示例
- `05_PWM/` - PWM 输出示例
- `06_adc/` - ADC 采集示例
- `07_uart/` - UART 串口通信示例
- `08_80MHz/` - 80MHz 时钟配置示例
- `09_adc_dma_40MHz_1MHz/` - ADC + DMA 示例
- `11_adc_dma_32MHz_4MHz/` - ADC + DMA 示例
- `12_FFT/` - FFT 信号处理示例
- `13_printf/` - `printf` 串口打印示例
- `14_adc_dma_2ch/` - 双通道 ADC + DMA 示例
- `15_adc_dma_time_trigger/` - 定时触发 ADC + DMA 示例
- `16_DDS_9910/` - DDS 频率合成示例
- `17_Capture/` - 捕获功能示例
- `19_Capture_frency/` - 频率捕获示例
- `20_ADF4351/` - ADF4351 射频芯片控制示例
- `21_I2c/` - I2C 通信示例


 使用方法

1. 使用 TI Code Composer Studio (CCS) 导入对应示例工程。
2. 连接 MSPM0G3507 开发板或目标硬件。
3. 按需配置 `syscfg` 文件和目标板设置。
4. 构建工程并下载到板子上运行。

 适用环境

 MCU: TI MSPM0G3507
 开发工具: Texas Instruments Code Composer Studio (CCS)
 操作系统: Windows

说明

本仓库适合作为 MSPM0G3507 学习与实验参考，包含多个外设与驱动示例。你可以直接在 CCS 中打开某个示例目录进行编译调试。
