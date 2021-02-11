# M5Camera

<el-tag effect="plain">SKU:U017</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/unit/m5camera/unit_m5camera_01.webp"><img src="assets/img/product_pics/unit/m5camera/unit_m5camera_02.webp"></div>

## Description

**M5Camera** is a development board for image recognition. It features an ESP32(4M Flash + 520K RAM) chip and 2-Megapixel camera (OV2640).**M5Camera** offers plenty of storage, with an extra 4 Mbyte PSRAM.  It also supports image transmission via Wi-Fi and debugging through USB Type-C port.

The hardware comes preloaded software, programmed by ESP-IDF. It is an application to run Wi-Fi camera. The output image is size 600*800, since it's 2MP, you sure can optimize the software to output the maximum size of photos.

what this software can do?
- Power the board via USB type-C or GROVE
- Use your phone to Wi-Fi scan an AP name start with 'm5stack-' and click to connect this AP.
- Open up web browser on your phone and visit <mark>192.168.4.1</mark>
- Then here comes the picture. Video is about 5-6 frames per seconds. not super fast.

<img src="assets/img/product_pics/unit/unit_m5camera_05.webp" width="50%">

<img src="assets/img/product_pics/unit/unit_m5camera_06.webp" width="50%">

<img src="assets/img/product_pics/unit/m5camera/unit_m5camera_03.webp" width="50%">

## Product Features

- CP2104 USB-to-TTL converter
- ESP32-WROVER (PCB Antenna)
- WIFI image transmission
- OV2640 sensor

## Include

- 1x M5Camera
- 4x LEGO block
- 1x Type-C USB(20cm)

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>Flash</td>
      <td>4M</td>
   </tr>
   <tr>
      <td>RAM</td>
      <td>4MB</td>
   </tr>
   <tr>
      <td>Image Sensor</td>
      <td>OV2640</td>
   </tr>
   <tr>
      <td>Maximum resolution</td>
      <td>200w pixel</td>
   </tr>
   <tr>
      <td>Output format</td>
      <td>YUV(422/420)/YCbCr422,RGB565/555,8-bit compressed data,8-/10-bit Raw RGB data</td>
   </tr>
   <tr>
      <td>Maximum image transmission rate</td>
      <td>UXGA/SXGA: 15fps, SVGA: 30fps, CIF: 60fps</td>
   </tr>
   <tr>
      <td>FOV</td>
      <td>65°</td>
   </tr>
   <tr>
      <td>CCD Size</td>
      <td>1/4 inch</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>17g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>41g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>40*48*11mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>75*45*30mm</td>
   </tr>
</table>

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Unit/M5-Camera-B/wifi_ap/EasyLoader_M5CAMERA_B_wifi_ap.exe"><el-button type="primary">download EasyLoader</el-button></a>

>1.EasyLoader is a simple and fast program burner. Every product page in EasyLoader provides a product-related case program. It can be burned to the master through simple steps, and a series of function verification can be performed. .

>2. After downloading the software, double-click to run the application, connect the M5 device to the computer through the data cable, select the port parameters, click **"Burn"** to start burning. (**For M5StickC burning, please Set the baud rate to 750000 or 115200**)

>3. Currently EasyLoader is only suitable for Windows operating system, compatible with M5 system adopts ESP32 as the control core host. Before installing for M5Core, you need to install CP210X driver (you do not need to install with M5StickC as controller)[Click here to view the driver installation tutorial](en/related_documents/M5Burner#install-usb-driver)


## PinMap


**Camera Interface PinMap**

| *Interface*             | *Camera Pin*| *M5Camera*  |
| :-------------------  | :--------:| :------:  |
| SCCB Clock            | SIOC     |IO23       |
| SCCB Data             | SIOD     |**IO22**       |
| System Clock          | XCLK     |IO27       |
| Vertical Sync         | VSYNC    |**IO25**       |
| Horizontal Reference  | HREF     |IO26       |
| Pixel Clock           | PCLK     |IO21       |
| Pixel Data Bit 0      | D2       |IO32       |
| Pixel Data Bit 1      | D3       |IO35       |
| Pixel Data Bit 2      | D4       |IO34       |
| Pixel Data Bit 3      | D5       |IO5        |
| Pixel Data Bit 4      | D6       |IO39       |
| Pixel Data Bit 5      | D7       |IO18       |
| Pixel Data Bit 6      | D8       |IO36       |
| Pixel Data Bit 7      | D9       |IO19       |
| Camera Reset          | RESET    |IO15       |
| Camera Power Down     | PWDN     | / |
| Power Supply 3.3V     | 3V3      | 3V3       |
| Ground                | GND      | GND       |

**GROVE Interface**

| *Grove*         | *M5Camera*  |
| :-----------: | :------:  |
| SCL           | IO13      |
| SDA           | **IO4**      |
| 5V            | 5V        |
| GND           | GND       |

**LED Interface**

| *LED*         |*M5Camera*  |
| :-----------:| :------:  |
| LED_Pin      | IO14      |

**The following tables are Reserved Chip Interfaces**

**BME280 Interface**

*I2C address 0x76.*

| *BMP280*      |*M5Camera*  |
| :-----------: | :------:  |
| SCL           | IO23      |
| SDA           | IO22      |

**MPU6050 Interface**

*I2C address 0x68.*

| *MPU6050*     | *M5Camera*  |
| :-----------: | :------:  |
| SCL           | IO23      |
| SDA           | IO22      |

**MIC(SPM1423) Interface**

| *MIC(SPM1423)*     | *M5Camera*  |
| :-----------: | :------: |
| CLK           |IO4|
| DATA           |IO2|



<img src="assets/img/product_pics/unit/m5camera/unit_m5camera_04.webp" width="30%" height="30%">


**NOTE:**

1. **Camera Power Down** pin does not need to be connected to ESP32 GPIO. Instead it may be pulled down to ground with 10 kOhm resistor.

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/m5-docs_table/Product_compared.pdf"><el-button type="primary">View M5 camera series/product differences</el-button></a>

## Related Link

- **Datasheet** - [ESP32](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32_datasheet_en.pdf) - [OV2640](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/unit/OV2640DS_en.pdf)

## Example

### Firmware

- **[M5Camera](https://github.com/m5stack/M5Stack-Camera/tree/master/wifi/wifi_ap/firmware/M5Camera)**

### Arduino

- **[M5Camera-Arduino](https://github.com/espressif/arduino-esp32/tree/master/libraries/ESP32/examples/Camera/CameraWebServer)**

### Code

 - **[Face recognition](https://github.com/m5stack/M5Stack-Camera/tree/master/face_recognize/firmware/M5Camera)**

 - **[Serial communication-M5Camera](https://github.com/m5stack/M5Stack-Camera/tree/master/uart/firmware/M5Camera)**

 - **[Serial communication-M5Core](https://github.com/m5stack/M5Stack-Camera/tree/master/uart/arduino)**（The serial communication routine is the communication between the camera and the M5Core.）

 - **[QRcode](https://github.com/m5stack/M5Stack-Camera/tree/master/qr)**

 - **[MPU6050](https://github.com/m5stack/M5Stack-Camera/tree/master/mpu6050/firmware/M5Camera)**（Gyro Example after soldering **MPU6050**）

 - **[Tutorial&Quick-Start](en/quick_start/m5camera/m5camera_quick_start)**

### Source Code
 - **[M5Camera](https://github.com/m5stack/M5Stack-Camera)**

## Schematic

### Power circuit

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/m5-docs_schematic/unit/m5camera_sch_01.webp">

### Chip peripheral circuit

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/m5-docs_schematic/unit/m5camera_sch_02.webp">

### USB to serial port part of the circuit

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/m5-docs_schematic/unit/m5camera_sch_03.webp">

## Video

**M5Camera Case - Image transmission between M5Camera and M5Core**

<video class="video_size" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Blog/Twitch201812/M5Camera.mp4" type="video/mp4">
</video>

<el-divider content-position="right">Last updated: 2020-12-14</el-divider>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/esp-32-camera-psram';

   var quickstart_link = 'https://docs.m5stack.com/#/en/quick_start/m5camera/m5camera_quick_start';

   anchor_search(purchase_link,quickstart_link);
   scrollFunc();

</script>
