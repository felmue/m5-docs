# FIRE {docsify-ignore-all}

<el-tag effect="plain">SKU:K007</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/core/fire/product_pic_fire.webp"> <img src="assets/img/product_pics/core/fire/m5_fire_01.webp"></div>

## 教程&快速上手

选择你想使用的开发平台，查看对应的教程&快速上手。

<a href="/#/zh_CN/quick_start/m5core/m5stack_core_get_started_MicroPython"><el-tag effect="plain">UIFlow</el-tag></a>
<a href="/#/zh_CN/arduino/arduino_development"><el-tag effect="plain">Arduino</el-tag></a>

## 描述

**M5Stack FIRE Kit** 是M5Stack开发套件系列中的一款，主打高性能的开发套件.它作为Gray套件的升级版，提供九轴运动传感器（六轴姿态加速度计+三轴磁力计），配备更强性能的硬件资源：16M Flash, 4M PSRAM, 增强型 Base（M5GO 底座和M5GO 充电底座），更大容量的电池等.对于对硬件性能方面有所要求的开发者来说,Fire是一个非常不错的选择.

我们可以在很多的应用场景中使用姿态传感器用作:检测加速度、角度、轨迹延伸等数据.根据这些去制作出相关的产品，如运动数据采集器，3D远程手势控制器等.

M5Stack Fire 配有三个可分离部件. 顶部与其他的M5主机一样，放置了电路板，芯片，LCD屏幕，2.4G天线，，各种电子元器件以及一些接口组件.中间部分称为 M5GO 底座，提供锂电池，M-BUS总线母座，LED条和三个GROVE拓展端口. 位于最底部的是充电底座，可以与 M5GO 底座通过 POGO 引脚进行连接，进行充电.

快速成型，超低门槛，直达产品级，M5Stack 开发板会是你物联网开发的不二之选.传统开发板只能用作验证和学习，M5的出现赋予了开发板更多的可能性，M5Stack 开发板采用了工业级外壳，再加上精致的外观设计，整体性能稳定，除了验证和学习的功能之外，还可以加速开发和产品化的进程.采用**ESP32**物联网芯片.集成 Wi-Fi 和蓝牙模块，拥有4MB的SPI闪存，双核低功耗的它在多种应用场景中有着非凡表现.由30多个M5Stack 可堆叠模块，40 多个可扩展单元组成的硬件拓展体系，能够快速的帮助你搭建和验证你的物联网产品.

支持的开发平台和程序语言：Arduino，[UIFlow](http://flow.m5stack.com) 的 Blockly 语言，Micropython. 无论你的开发和编程能力处在何种水平，M5Stack都将协助你，逐步的将想法变为现实.

如果你开发过 ESP8266，你会发现 ESP32 是 ESP8266 的完美升级版.相比之下，ESP32 具有更多 GPIO ，更多的模拟输入和两个模拟输出，多个外设接口（如备用UART）.官方开发平台 ESP-IDF 已经移植了 FreeRTOS ，借助双核与实时操作系统，能使你更加高效的去组织你的程序代码，优化程序的执行效率.

**注意：** 

Fire 中的 GPIO 16 / 17 默认与PSRAM连接，因此当你在连接或是堆叠其他功能模块时，需要注意避免与这两个引脚冲突，防止设备不正常工作，产生不稳定的现象.

**开关机操作：**

* 开机：单击左侧红色电源键

* 关机：快速双击左侧红色电源键

## 产品特性

- 基于ESP32开发
- 外挂PSRAM
- 内集成3轴陀螺仪、3轴加速计和3轴磁力计
- 内置扬声器，按键，LCD屏幕，电源/复位按键
- TF 卡插槽（最大可拓展16GB）
- 内置锂电池
- 背部磁吸式设计
- 可拓展的引脚与接口
- M-Bus总线母座
- 开发平台 [UIFlow](http://flow.m5stack.com), [MicroPython](http://micropython.org/), [Arduino](http://www.arduino.cc)

## 包含

-  1x FIRE
-  1x M5GO 充电底座
-  2x LEGO积木
-  5x LEGO连接件
-  1x M3六角扳手
-  1x Type-C USB(100cm)
-  1x 使用手册

## 应用

- 物联网控制器
- STEM教育
- DIY作品
- 智能家居设备

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>主控资源</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>ESP32</td>
      <td>240MHz dual core, 600 DMIPS, 520KB SRAM, Wi-Fi, dual mode Bluetooth</td>
   </tr>
   <tr>
      <td>Flash闪存</td>
      <td>16MB Flash + 4MB PSRAM </td>
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
      <td>IPS屏幕</td>
      <td>2 inch, 320x240 Colorful TFT LCD, ILI9342C，最高亮度853nit</td>
   </tr>
   <tr>
      <td>扬声器</td>
      <td>1W-0928</td>
   </tr>
      <tr>
      <td>麦克风</td>
      <td>MEMS Analog BSE3729 Microphone</td>
   </tr>
   <tr>
      <td>LED</td>
      <td>SK6812 3535 RGB LED x 10</td>
   </tr>
   <tr>
      <td>MEMS</td>
      <td>BMM150 + SH200Q/MPU6886</td>
   </tr>
   <tr>
      <td>天线</td>
      <td>2.4G 3D天线</td>
   </tr>
   <tr>
      <td>底座接口</td>
      <td>PortA(I2C)、PortB(GPIO)、PortC(UART)</td>
   </tr>
   <tr>
      <td>电池</td>
      <td>500 mAh @ 3.7V, inside  vb</td>
   </tr>
   <tr>
      <td>工作温度</td>
      <td>32°F to 104°F ( 0°C to 40°C )</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>62.3g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>162g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>54mm x 54mm x 30.5mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>105mm x 65mm x 40mm</td>
   </tr>
   <tr>
      <td>外壳材质</td>
      <td>Plastic ( PC )</td>
   </tr>
</table>

### M5GO底座

[点击查看详情参数](zh_CN/base/m5go_bottom)

## EasyLoader

>EasyLoader是一个简洁快速的程序烧录器，其内置了一个产品相关的案例程序，通过简单步骤将其烧录至主控，即可进行一系列的功能验证.**(程序烧录前，请根据设备类型安装相应驱动程序. M5Core型主机[请点击此处查看CP210X驱动安装教程](zh_CN/arduino/arduino_development?id=安装串口驱动)，M5StickC/V/T/ATOM系列可免驱动使用)**

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/CORE/EasyLoader_UIFlow_v1.4.5.exe">Windows</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/Core/FIRE.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>案例描述:</p>
            <p>加载UIFlow固件，内置演示程序支持加速计，LED BAR，麦克风，按键及部分外设传感器的测试，固件可用于UIFlow图形化编程.</p>
        </div>
    </div>
</div>


## 管脚映射

**LCD 屏幕 & TF 卡**

LCD 像素：320x240
TF 卡最大支持 16GB

<table>
 <tr><td>ESP32 Chip</td><td>GPIO23</td><td>GPIO19</td><td>GPIO18</td><td>GPIO14</td><td>GPIO27</td><td>GPIO33</td><td>GPIO32</td><td>GPIO4</td></tr>
 <tr><td>ILI9342C</td><td>MOSI/MISO</td><td>/</td><td>CLK</td><td>CS</td><td>DC</td><td>RST</td><td>BL</td><td> </td></tr>
 <tr><td>TF卡</td><td>MOSI</td><td>MISO</td><td>CLK</td><td> </td><td> </td><td> </td><td> </td><td>CS</td></tr>
</table>

**按键 & 喇叭**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO39</td><td>GPIO38</td><td>GPIO37</td><td>GPIO25</td></tr>
 <tr><td>按键引脚</td><td>BUTTON A</td><td>BUTTON B</td><td>BUTTON C</td></tr>
 <tr><td>喇叭</td><td> </td><td> </td><td> </td><td>喇叭引脚</td></tr>
</table>

**GROVE 接口 A & IP5306**

电源管理芯片 (IP5306) 是定制 I2C 版本，它的 I2C 地址是 0x75。点击[这里](https://github.com/m5stack/M5-Schematic/blob/master/Core/IIC_IP5306_REG_V1.4.pdf)查看 IP5306 的寄存器手册。

<table>
 <tr><td>ESP32 Chip</td><td>GPIO22</td><td>GPIO21</td><td>5V</td><td>GND</td></tr>
 <tr><td>GROVE A</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
 <tr><td>IP5306</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

**IP5306充/放电，电压参数**

<table>
   <tr style="font-weight:bold;text-align:center" >
      <td>充电</td>
      <td><td>
      <td>放电</td>
   </tr>
   <tr>
      <td>0.00 ~ 3.40V -> 0%</td>
      <td><td>
      <td>4.20 ~ 4.07V -> 100%</td>
   </tr>
   <tr>
      <td>3.40 ~ 3.61V -> 25%</td>
      <td><td>
      <td>4.07 ~ 3.81V -> 75%</td>
   </tr>
   <tr>
      <td>3.61 ~ 3.88V -> 50%</td>
      <td><td>
      <td>3.81 ~ 3.55V -> 50%</td>
   </tr>
   <tr>
      <td>3.88 ~ 4.12V -> 75%</td>
      <td><td>
      <td>3.55 ~ 3.33V -> 25%</td>
   </tr>
   <tr>
      <td>4.12 ~   /   -> 100%</td>
      <td><td>
      <td>3.33 ~ 0.00V -> 0%</td>
   </tr>
</table>

**MPU6886 3轴加速计+3轴陀螺仪**

MPU6886 I2C address 0x68

<table>
 <tr><td>ESP32 Chip</td><td>GPIO22</td><td>GPIO21</td><td>5V</td><td>GND</td></tr>
 <tr><td>MPU6886</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

**BMM150 3轴磁力计**

BMM150 I2C address 0x10

<table>
 <tr><td>ESP32 Chip</td><td>GPIO22</td><td>GPIO21</td><td>5V</td><td>GND</td></tr>
 <tr><td>BMM150</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

## M5GO 底座管脚

**GROVE 接口 B**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO36</td><td>GPIO26</td><td>5V</td><td>GND</td></tr>
 <tr><td>GROVE B</td><td>GPIO36</td><td>GPIO26</td><td>5V</td><td>GND</td></tr>
</table>

**GROVE 接口 C**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO16</td><td>GPIO17</td><td>5V</td><td>GND</td></tr>
 <tr><td>GROVE C</td><td>RXD</td><td>TXD</td><td>5V</td><td>GND</td></tr>
</table>

**LED 灯条 & 麦克风 & 扬声器**

<table>
 <tr><td>ESP32 Chip</td><td>GPIO15</td><td>GPIO34</td><td>GPIO25</td></tr>
 <tr><td>硬件</td><td>SIG Pin</td><td>MIC Pin</td><td> Speaker Pin</td></tr>
</table>


## M5端口说明

<table>
      <thead>
         <th>PORT</th>
         <th>PIN</th>
         <th>备注:</th>
      </thead>
      <tbody>
      <tr>
         <td>PORT-A(红色)</td>
         <td>G21/22</td>
         <td>I2C</td>
      </tr>
      <tr>
         <td>PORT-B(黑色)</td>
         <td>G26/36</td>
         <td>DAC/ADC</td>
      </tr>
      <tr>
         <td>PORT-C(蓝色)</td>
         <td>G16/17</td>
         <td>UART</td>
      </tr>
    </tbody>
</table>

## ESP32 ADC/DAC

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

在使用GPIO15的RGB LED时，建议初始化引脚pinMode(15, OUTPUT_OPEN_DRAIN);
有关引脚分配和引脚重新映射的更多信息，请参考[ESP32 datasheet](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32_datasheet_cn.pdf)


<a href="#zh_CN/uiflow/introduction.md"><button type="button" class="btn btn-primary">查看固件烧录教程</button></a>

## 相关链接

- **Datasheet**

    - [ESP32](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32_datasheet_cn.pdf)
    - [MPU6886](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/MPU-6886-000193%2Bv1.1_GHIC_en.pdf)
    - [BMM150](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/BMM150_datasheet_en.pdf)
    - [SH200Q](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/SH200Q_en.pdf)
    - [IP5306](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/IIC_IP5306_REG_V1.4_cn.pdf)

- **API** 

   - [Arduino API](zh_CN/arduino/arduino_home_page?id=m5core_api)

## 原理图

- [原理图](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/schematic/Core/M5-Core-Schematic(20171206).pdf)

## 版本变更

<table class="fl-table">
   <thead>
   <tr>
      <th>上市日期</th>
      <th>产品变动</th>
      <th>备注：</th>
   </tr>
   </thead>    
   <tbody>
   <tr>
      <td>2018.6</td>
      <td>首次发售</td>
      <td>/</td>
   </tr>
   <tr>
      <td>2019.7</td>
      <td>MPU9250变更为SH200Q+BMM150、TN屏幕变更为IPS屏幕</td>
      <td>请将您的M5Stack库升级到最新版本(v0.2.8以上),以解决屏幕反色问题。</td>
   </tr>
   <tr>
      <td>2019.8</td>
      <td>SH200Q变更为MPU6886</td>
      <td>/</td>
   </tr>
   <tr>
      <td>2019.11</td>
      <td>电池容量600mAh变更为500mAh</td>
      <td>/</td>
   </tr>
   <tbody>
</table>


## 案例程序

### ArduinoIDE

- 点击[这里](https://github.com/m5stack/M5Stack/tree/master/examples/Basics)下载Arduino示例

## 相关视频

**m5stack 的简介**

<video class="video_size" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/LukeVideo/m5stack%E7%AE%80%E4%BB%8B%EF%BC%88%E4%B8%AD%E6%96%87%EF%BC%89.mp4" type="video/mp4">
</video>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-core/products/fire-iot-development-kit';

   var quickstart_link = 'https://docs.m5stack.com/#/zh_CN/quick_start/m5core/m5stack_core_quick_start';

   anchor_search(purchase_link,quickstart_link);
   scrollFunc();

</script>