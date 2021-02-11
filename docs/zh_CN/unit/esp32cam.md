# ESP32CAM

<el-tag effect="plain">SKU:U007</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/unit/unit_esp32cam_01.webp"><img src="assets/img/product_pics/unit/unit_esp32cam_02.webp"></div>

## 描述

**ESP32CAM** 是一款图像识别开发板，集成ESP32（4M Flash + 520K RAM）芯片和200万像素的摄像头（OV2640）.支持WiFi-图像传输和USB端口调试.

硬件上预装固件，通过ESP-IDF编程开发，运行WiFi-相机应用程序.默认程序输出图像尺寸为**600 * 800**，你可以通过优化程序输出更大尺寸.

这个程序是如何使用的?
- 打开手机Wi-Fi，扫描并连接名称以"m5stack-"开头的AP热点.
- 打开手机浏览器，访问<mark>192.168.4.1</mark>,进入监控页面实时获取拍摄视频.
- 视频帧率大约在每秒5-6帧.

因为模块可以生成 WIFI 热点 AP，所以可以用手机、PC 或其他设备通过 WIFI 无线获取摄像头图片，也可以通过模块的HY2.0-4P 接口有线获取摄像头图片。

## 产品特性

- 基于ESP32设计
- CP2104 USB TTL
- 2M像素图像传感器
- 65°视角

## 包含

- 1x ESP32CAM

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>Flash</td>
      <td>4MB</td>
   </tr>
   <tr>
      <td>RAM</td>
      <td>520KB</td>
   </tr>
   <tr>
      <td>图像传感器</td>
      <td>OV2640</td>
   </tr>
   <tr>
      <td>最大分辨率</td>
      <td>200万像素</td>
   </tr>
   <tr>
      <td>传输速率</td>
      <td>UXGA/SXGA: 15fps, SVGA: 30fps, CIF: 60fps</td>
   </tr>
   <tr>
      <td>输出格式</td>
      <td>YUV(422/420)/YCbCr422, RGB565/555, 8-bit compressed data</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>6g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>18g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>20.5*46.5*11.5mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>60*57*17mm</td>
   </tr>
</table>

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Unit/ESP32CAM/wifi_ap/EasyLoader__ESP32CAM_wifi_ap.exe"><el-button type="primary">点击下载EasyLoader</el-button></a>

>1.EasyLoader是一个简洁快速的程序烧录器，每一个产品页面里的EasyLoader都提供了一个与产品相关的案例程序，通过简单步骤将其烧录至主控，能够进行一系列的功能验证.

>2.下载软件后，双击运行应用程序，将M5设备通过数据线连接至电脑,选择端口参数，点击 **"Burn"** 即可开始烧录.(**为M5StickC烧录时，请将波特率设置在750000或115200**)

?>3.目前EasyLoader仅适用于Windows操作系统、兼容M5体系采用ESP32作为控制核心的主机.在为M5Core烧录前需要安装CP210X驱动程序（使用M5StickC作为控制器的则无需安装）[点击此处查看驱动安装教程](zh_CN/related_documents/M5Burner#安装串口驱动)

## 管脚映射

**相机管脚映射**

| *接口*             | *OV2640 Pin*| *ESP32Cam*    |
| :-------------------  | :--------:| :--------:  |
| SCCB Clock            | SIOC      | IO23        |
| SCCB Data             | SIOD      | IO22        |
| System Clock          | XCLK      | IO27        |
| Vertical Sync         | VSYNC     | IO25        |
| Horizontal Reference  | HREF      | IO26        |
| Pixel Clock           | PCLK      | IO21        |
| Pixel Data Bit 0      | D2        | IO17        |
| Pixel Data Bit 1      | D3        | IO35        |
| Pixel Data Bit 2      | D4        | IO34        |
| Pixel Data Bit 3      | D5        | IO5         |
| Pixel Data Bit 4      | D6        | IO39        |
| Pixel Data Bit 5      | D7        | IO18        |
| Pixel Data Bit 6      | D8        | IO36        |
| Pixel Data Bit 7      | D9        | IO19        |
| Camera Reset          | RESET     | IO15        |
| Camera Power Down     | PWDN      |*see Note 1* |
| Power Supply 3.3V     | 3V3       | 3V3         |
| Ground                | GND       | GND         |

**HY2.0-4P 接口**

| *HY2.0-4P*         | *ESP32Cam*    |
| :-----------: | :--------:  |
| SCL           | IO4        |
| SDA           | IO13        |
| 5V            | 5V          |
| GND           | GND         |

**LED 接口**

| *LED*         | *ESP32Cam*    |
| :-----------: | :--------:  |
| LED_Pin           | IO16        |

**reserved chip 接口**

**BME280 接口**

*I2C 地址 0x76*

| *BME280*         | *ESP32Cam*    |
| :-----------: | :--------:  |
| SCL           | IO4         |
| SDA           | IO13        |

**MPU6050 接口**

*I2C 地址是 0x68*

| *MPU6050*         | *ESP32Cam*    |
| :-----------: | :--------:  |
| SCL           | IO4         |
| SDA           | IO13        |

**麦克风(SPQ2410) 接口**

| *SPQ2410*            | *ESP32Cam*  |
| :-----------: | :------:  |
| OUT           | IO32      |

**注意：**

1. OV2640 芯片的 **PIN8（PDWN）**引脚为使能引脚，在该主板中通过12KΩ下拉电阻接地使能，进入工作模式.当 PIN8（PDWN）引脚上拉高电平时，将进入**Camera Power Down**模式.

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/m5-docs_table/Product_compared.pdf"><el-button type="primary">查看M5摄像头系列/产品区别</el-button></a>

## 相关链接

- **数据手册** - [ESP32](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32_datasheet_cn.pdf) - [OV2640](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/unit/OV2640DS_en.pdf)

## 原理图

- **[原理图](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/schematic/esp32-cam/M5CAM-ESP32-A1-POWER.pdf)**

## 案例程序


## 出厂固件（WiFi传输图像）

- **[ESP32CAM 固件](https://github.com/m5stack/M5Stack-Camera/tree/master/wifi/wifi_ap/firmware/ESP32-Camera)**


- **[串口通信-ESP32CAM](https://github.com/m5stack/M5Stack-Camera/tree/master/uart/firmware/ESP32-Camera)**

- **[串口通信-M5Core](https://github.com/m5stack/M5Stack-Camera/tree/master/uart/arduino/uart)**（串口通信例程为，摄像头与M5Core之间通信）

- **[教程&快速上手](zh_CN/quick_start/m5camera/m5camera_quick_start)**

### Arduino

- **[ESP32CAM-Arduino](https://github.com/espressif/arduino-esp32/tree/master/libraries/ESP32/examples/Camera/CameraWebServer)**


## 相关视频

**ESP32CAM case - 01**

<video class="video_size" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Blog/Twitch201903/esp32cam_webcam_01.mp4" type="video/mp4">
</video>

**M5Camera 的应用 - 02**

<video class="video_size" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Blog/Twitch201901/The%20M5Camera%20works.mp4" type="video/mp4">
</video>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/esp32-camera';
   var quickstart_link = 'https://docs.m5stack.com/#/zh_CN/quick_start/m5camera/m5camera_quick_start'

   anchor_search(purchase_link,quickstart_link);
   scrollFunc();

</script>