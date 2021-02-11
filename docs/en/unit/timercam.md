# Timer Camera {docsify-ignore-all}

<el-tag effect="plain">SKU:U082</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/unit/timercamera/timercamera.webp"></div>

## Tutorial&Quick-Start

Choose the development platform you want to use, view the corresponding tutorial&quick-Start.

<a href="/#/en/quick_start/timer_cam/quick_start_cameratool"><el-tag effect="plain">Camera-Tool</el-tag></a>
<a href="/#/en/quick_start/timer_cam/quick_start_uiflow"><el-tag effect="plain">UIFlow</el-tag></a>
<a href="/#/en/quick_start/timer_cam/quick_start_arduino"><el-tag effect="plain">Arduino</el-tag></a>

## Description

**Timer Camera** is a camera module based on the ESP32 with 8MB of integrated with PSRAM. The 3 million (3MP) pixel camera (ov3660) ,DFOV 66.5 ° and can shoot a maximum of 2048x1536 resolution photos. There is a LED status indicator and reset button on the board. Timer Camera is designed to have ultra-low power consumption. Through the use of the RTC (BM8563), timing, sleep and wake-up functions can be utilized.

In sleep mode, the current consumption of the whole machine is only 2μA. After the scheduled photo taking function(one photo per hour) is turned on, the battery can work continuously for more than one month. The module supports WiFi image transmission and USB port debugging. The bottom HY2.0-4P port output can be connected to other peripherals. In order to facilitate DIY, the battery interface is reserved on the board. Using the M5Burner firmware burning tool, time-cam can be set directly with the Camera-Tool, and TimerCamera data can be processed in UIFlow.

>The low-power power management solution adopted by the Timer Camera series is different from the CORE and StickC devices. When in use, the PWR button is used as a power-on button(long press 2s). If you need to shut down the device, you need to use the software API or press the Reset button on the PCB.

## Product Features

- Design based on ESP32
- WiFi image/video transmission
- Timed sleep wake up
- Status indicator
- Ultra low power design
- Programming platform：ESP-IDF/Arduino/UIFlow

## Includes

- 1x Timer Camera

## Applications

- Take pictures regularly
- Remote video monitoring

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>PSRAM</td>
      <td>8MB</td>
   </tr>
   <tr>
      <td>Flash</td>
      <td>4M</td>
   </tr>
   <tr>
      <td>Image Sensor</td>
      <td>OV3660</td>
   </tr>
   <tr>
      <td>Maximum resolution</td>
      <td>300w pixels</td>
   </tr>
   <tr>
      <td>Output format</td>
      <td>8-/10-Bit RAW, RGB and YCbCr output, compression.</td>
   </tr>
   <tr>
      <td>Maximum image transmission rate (OV3660)</td>
      <td>
         2048x1536: 15fps /
         1080p: 20fps /
         720p: 45fps	 /
         XGA(1024x768) : 45fps /
         VGA(640x480) : 60fps /
         QVGA(320x240) : 120fps
      </td>
   </tr>
   <tr>
      <td>DFOV</td>
      <td>66.5°</td>
   </tr>
   <tr>
      <td>Net Weight</td>
      <td>6g</td>
   </tr>
   <tr>
      <td>Gross Weight</td>
      <td>17g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>45*20*12mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>60*60*15mm</td>
   </tr>
</table>

## EasyLoader

>EasyLoader is a concise and fast program writer, which has a built-in case program related to the product. It can be burned to the main control by simple steps to perform a series of function verification. 

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/TIMECAM/EasyLoader_TimerCamera_AP.exe">Windows</a>
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/MacOS/TIMECAM/EasyLoader_TimerCamera_AP.dmg">MacOS</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/Unit/timer_cameraX.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>Description:</p>
            <p>(This video was shot for timercamera X)Connect the TimerCAM hotspot(AP)，input password 12345678 and open 192.168.4.1 in the browser to view the image. If you need to use the timing photo function, please refer to the quick start guide</p>
        </div>
    </div>
</div>

## PinMap

**Camera Interface PinMap**

| *Interface*             | *Camera Pin*| *TimerCamera*  |
| :-------------------  | :--------:| :------:  |
| SCCB Clock            | SIOC     |IO23        |
| SCCB Data             | SIOD     |IO25       |
| System Clock          | XCLK     |IO27       |
| Vertical Sync         | VSYNC    |IO22       |
| Horizontal Reference  | HREF     |IO26       |
| Pixel Clock           | PCLK     |IO21       |
| Pixel Data Bit 0      | D0       |IO32       |
| Pixel Data Bit 1      | D1       |IO35       |
| Pixel Data Bit 2      | D2       |IO34       |
| Pixel Data Bit 3      | D3       |IO5        |
| Pixel Data Bit 4      | D4       |IO39       |
| Pixel Data Bit 5      | D5       |IO18       |
| Pixel Data Bit 6      | D6       |IO36       |
| Pixel Data Bit 7      | D7       |IO19       |
| Camera Reset          | RESET    |IO15       |
| Camera Power Down     | PWDN     |-1         |
| Power Supply 3.3V     | 3V3      | 3V3       |
| Ground                | GND      | GND       |

**GROVE Interface**

| *Grove*         | *TimerCamera*  |
| :-----------: | :------:  |
| SCL           | IO13      |
| SDA           | IO4       |
| 5V            | 5V        |
| GND           | GND       |

**LED Interface**

| *LED*         | *TimerCamera*  |
| :-----------:| :------:  |
| LED_Pin      | IO2     |

**BAT Interface**

| *BAT*         | *TimerCamera*  |
| :-----------:| :------:  | 
| BAT_ADC_Pin     | IO38     | 
| BAT_HOLD_Pin     | IO33     | 

## Related Link

- **datasheet**
   - [ESP32](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32_datasheet_cn.pdf)
   - [OV3660](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/unit/OV3660_CSP3_DS_1.3_sida.pdf)

## Schematic

[TimerCAM_A1-ESP32_SUBSYS](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/schematic/TimerCAM/TimerCAM_A1-ESP32_SUBSYS.pdf)

[TimerCAM_A2-PMS_UART](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/schematic/TimerCAM/TimerCAM_A2-PMS_UART.pdf)

## Example

### Arduino

- **[TimerCamera-Arduino](https://github.com/m5stack/TimerCam-arduino)**

### SourceCode

- **[TimerCamera](https://github.com/m5stack/TimerCam-idf)**

### Firmware

**You can download and burn firmware with [M5Burner](https://m5stack.com/pages/download)**

### Tutorial

**[Use Camera-Tool](en/quick_start/timer_cam/quick_start_cameratool) to take pictures**

**[Use HTTP Cloud Image Interface Service-UIFlow](en/quick_start/timer_cam/quick_start_uiflow) to get pictures**

**[Use Arduino](en/quick_start/timer_cam/quick_start_arduino) development**

## Video

<video class="video_size" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/Unit/TimerCAM.mp4" type="video/mp4">
</video>

<el-divider content-position="right">Last updated: 2020-12-14</el-divider>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5stack-new-arrival/products/esp32-psram-timer-camera-ov3660';

   var quickstart_link = 'https://docs.m5stack.com/#/en/quick_start/timer_cam/quick_start_list';

   anchor_search(purchase_link,quickstart_link);
   scrollFunc();

</script>
