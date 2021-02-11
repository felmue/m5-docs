# TOUGH

<!-- <el-tag effect="plain">SKU:K010</el-tag> -->

<!-- <div class="product_pic"><img class="pic" src="assets/img/product_pics/core/tough/tough_01.webp"><img class="pic" src="assets/img/product_pics/core/tough/tough_02.webp"></div> -->

## 描述

**TOUGH** 是M5Stack开发套件系列中面向工业场景的嵌入式主控。主控ESP32型号为D0WDQ6-V3，具有两个可以单独控制的 Xtensa® 32-bit LX6 处理器，主频高达240Mhz，支持WiFi与蓝牙功能，板载16MB Flash与8MB PSRAM，可通过TYPE-C接口下载程序，强劲的配置满足复杂应用的资源开销。正面搭载一块2.0寸电阻式触摸屏。内建的RTC模块可提供精准计时功能。电源部分搭载AXP192电源管理芯片。同时机身内配备了TF-card(microSD)卡槽与扬声器，采用I2S数字音频接口的功放芯片，能有效防止音频信号失真。

## 产品特性

- 基于 ESP32 开发，支持WiFi、蓝牙
- 16M Flash，8M PSRAM
- 内置扬声器，电源指示灯, RTC，I2S功放，电阻式触摸屏幕，电源键，复位按键
- TF卡插槽(支持最大16GB)
- 开发平台 [UIFlow](http://flow.m5stack.com), [MicroPython](http://micropython.org/), [Arduino](http://www.arduino.cc)

## 包含

-  1x M5Stack TOUGH
-  1x Type-C USB(20cm)

## 应用

- 工业控制器

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>主控资源</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>ESP32-D0WDQ6-V3</td>
      <td>240MHz dual core, 600 DMIPS, 520KB SRAM, Wi-Fi, dual mode Bluetooth</td>
   </tr>
   <tr>
      <td>Flash</td>
      <td>16MB</td>
   </tr>
   <tr>
      <td>PSRAM</td>
      <td>8MB</td>
   </tr>
   <tr>
      <td>输入电压</td>
      <td>5V @ 500mA</td>
   </tr>
   <tr>
      <td>主机接口</td>
      <td>TypeC x 1, GROVE(I2C+I/0+UART) x 1</td>
   </tr>
   <tr>
      <td>IPS LCD屏幕</td>
      <td>2.0"@320*240 ILI9342C</td>
   </tr>
   <tr>
      <td>电阻式触摸屏驱动IC</td>
      <td>NS2009</td>
   </tr>
   <tr>
      <td>扬声器</td>
      <td>1W-0928</td>
   </tr>
   <tr>
      <td>I2S功放</td>
      <td>NS4168</td>
   </tr>
   <tr>
      <td>RTC</td>
      <td>BM8563</td>
   </tr>
   <tr>
      <td>PMU</td>
      <td>AXP192</td>
   </tr>
   <tr>
      <td>USB芯片</td>
      <td>CP2104</td>
   </tr>
   <tr>
      <td>DC-DC升压</td>
      <td>SY7088</td>
   </tr>
   <tr>
      <td>TF卡槽</td>
      <td>支持最大16G</td>
   </tr>
   <tr>
      <td>锂电池接口</td>
      <td>MX1.25mm直插2P</td>
   </tr>
   <tr>
      <td>天线</td>
      <td>2.4G 3D天线</td>
   </tr>
</table>


## EasyLoader

>EasyLoader是一个简洁快速的程序烧录器，其内置了一个产品相关的案例程序，通过简单步骤将其烧录至主控，即可进行一系列的功能验证.**(程序烧录前，请根据设备类型安装相应驱动程序. M5Core型主机[请点击此处查看CP210X驱动安装教程](zh_CN/arduino/arduino_development?id=安装串口驱动)**

- **Windows** 
   - [FactoryTest](https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/CORE/EasyLoader_M5Tough_FactoryTest.exe)

## 管脚映射

**LCD 屏幕 & TF Card**

LCD 像素：320x240
TF 卡最大支持 16GB

<table>
 <tr><td>ESP32 Chip</td><td>GPIO38</td><td>GPIO23</td><td>GPIO18</td><td>GPIO5</td><td>GPIO15</td><td></td><td> </td><td> </td></tr>
 <tr><td>AXP192 Chip</td><td> </td><td> </td><td> </td><td> </td><td> </td><td>AXP_IO4</td><td>AXP_LD03</td><td>AXP_LDO2</td></tr>
 <tr><td>ILI9342C</td><td>MISO</td><td>MOSI</td><td>SCK</td><td>CS</td><td>DC</td><td>RST</td><td>BL</td><td>PWR</td></tr>
</table>

<table>
<tr><td>ESP32 Chip</td><td>GPIO38</td><td>GPIO23</td><td>GPIO18</td><td>GPIO4</td></tr>
<tr><td>TF Card</td><td>MISO</td><td>MOSI</td><td>SCK</td><td>CS</td></tr>
</table>

**电阻式触摸屏**

<table>
 <tr><td>ESP32 chip</td><td>GPIO21</td><td>GPIO22</td><td>GPIO39</td></tr>
 <tr><td>Res.TOUCH/NS2009</td><td>SDA</td><td>SCL</td><td>PENIRQ</td></tr>
</table>

**NS4168功放**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO12</td><td>GPIO0</td><td>GPIO2</td><td>AXP_IO2</td></tr>
 <tr><td>NS4168</td><td>BCLK</td><td>LRCK</td><td>DATA</td><td>SPK_EN</td></tr>
</table>

**RTC**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO21</td><td>GPIO22</td><td></td></tr>
 <tr><td>AXP192</td><td></td><td></td><td>AXP_PWR</td><td>AXP_LDO1</td></tr>
 <tr><td>BM8563</td><td>SDA</td><td>SCL</td><td>INT</td><td>PWR</td></tr>
</table>

**USB转串口下载**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO1</td><td>GPIO3</td></tr>
 <tr><td>CP2104</td><td>RXD</td><td>TXD</td></tr>
</table>

**内部I2C连接**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO21</td><td>GPIO22</td></tr>
 <tr><td>AXP192</td><td>SDA</td><td>SCL</td></tr>
 <tr><td>BM8563</td><td>SDA</td><td>SCL</td></tr>
 <tr><td>NS2009</td><td>SDA</td><td>SCL</td></tr>
</table>

## TOUGH M-BUS示意图

<img class="pic" src="assets/img/product_pics/core/core2/core2_mbus.webp" width = "50%">

## M5Core2 端口说明

<table>
      <thead>
         <th>PORT</th>
         <th>PIN</th>
         <th>备注:</th>
      </thead>
      <tbody>
      <tr>
         <td>PORT-A(红色)</td>
         <td>G32/33</td>
         <td>I2C</td>
      </tr>
    </tbody>
</table>

## ESP32 ADC/DAC可映射引脚

<table>
      <thead>
         <th>ADC1</th>
         <th>ADC2</th>
         <th>DAC1</th>
         <th>DAC2</th>
      </thead>
      <tbody>
      <tr>
         <td>8 通道</td>
         <td>10 通道</td>
         <td>2 通道</td>
         <td>2 通道</td>  
      </tr>
      <tr>
         <td>G32-39</td>
         <td>G0/2/4/12-15/25-27</td>
         <td>G25</td>
         <td>G26</td>
      </tr>
    </tbody>
</table>


有关引脚分配和引脚重新映射的更多信息，请参考[ESP32 datasheet](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32_datasheet_cn.pdf)


## 相关链接

- **Datasheet** 
   - [ESP32](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32_datasheet_cn.pdf)
   - [NS4168](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/NS4168_CN_datasheet.pdf)
   - [ILI9342C](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/ILI9342C-ILITEK.pdf)
   - [BM8563](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/BM8563_V1.1_cn.pdf)
   - [SY7088](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/SY7088-Silergy.pdf)
   - [AXP192](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/AXP192_datasheet_en.pdf)
   - [NS2009](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/tough/NS2009_C219024.pdf)

- **API** 

   - [Arduino API](zh_CN/arduino/arduino_home_page?id=tough_api)


## 原理图

<img src="assets/img/product_pics/core/tough/tough_sch.webp">

## 案例程序

### Arduino IDE

- [FactoryTest](https://github.com/m5stack/M5Tough/tree/master/examples/Basics/FactoryTest)
- [M5Tough-Lib](https://github.com/m5stack/M5Tough)


<script>
   anchor_search();
   scrollFunc();
</script>