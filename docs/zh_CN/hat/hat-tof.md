# ToF HAT

<el-tag effect="plain">SKU:U072</el-tag>

<div class="product_pic"><img src="assets\img\product_pics\hat\tof_hat\tof_hat_01.webp"><img src="assets\img\product_pics\hat\tof_hat\tof_hat_02.webp"></div>

## 描述

**ToF HAT**是一款专为M5SticKC设计的高精度激光测距传感器，内部集成ST激光测距芯片**VL53L0X**、**940nm VCSEL**发射器，通过测量激光信号到被测物体的往返时间，能够在不到30ms的时间内测量2m范围内的绝对距离.与传统测距不同的地方在于，无论检测目标的的反射率如何，它都能提供精确的距离测量数据.在一些对数据精度有一定要求的距离测量、障碍物识别项目中，**ToF HAT**能够有不错的表现.

## 产品特性

- 高精度
- 最大测量距离 2m
- 940nm 激光 VCSEL 
- 开发平台: Arduino, UIFlow(Blockly, Python)
- 安全方面：
    - 符合最新标准的1级激光设备
    - 标准IEC 60825-1:2014-第3版
- 通信协议：I2C地址为**0x29**(GOIO 0/26)

## 包含

- 1x ToF HAT

## 应用

- 障碍物识别
- 手势识别
- 激光测距
- 3D结构光成像（3D感应）
- 摄像机辅助（超快速自动对焦和景深图

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>通信协议</td>
      <td>I2C：0x29</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>4g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>8g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>24*20.3*13.8mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>37*35*18mm</td>
   </tr>
 </table>

## 相关链接

- **[VL53L0X Datasheet](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/hat/VL53L0X_en.pdf)**

## 原理图

<img src="assets\img\product_pics\hat\tof_hat\tof_hat_07.webp" width="50%">

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_M5StickC_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/HAT/ToF/EasyLoader_ToF_HAT.exe"><el-button type="primary">点击下载EasyLoader</el-button></a>

>1.EasyLoader是一个简洁快速的程序烧录器，每一个产品页面里的EasyLoader都提供了一个与产品相关的案例程序，通过简单步骤将其烧录至主控，能够进行一系列的功能验证.

>2.下载软件后，双击运行应用程序，将M5设备通过数据线连接至电脑,选择端口参数，点击 **"Burn"** 即可开始烧录.(**为M5StickC烧录时，请将波特率设置在750000或115200**)

## 案例程序

### 2. UIFlow

<img src="assets\img\product_pics\hat\tof_hat\tof.webp" width="50%">

### 1. Arduino

[单击此处下载完整Arduino代码](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Hat/tof-hat/Arduino/ToF)

### 管脚映射

<table>
 <tr><td>M5StickC</td><td>GPIO0</td><td>GPIO26</td><td>3.3V</td><td>GND</td></tr>
 <tr><td>ToF HAT</td><td>SDA</td><td>SCL</td><td>3.3V</td><td>GND</td></tr>
</table>

## 相关视频

<video class="video_size" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/HAT/ToF_HAT.mp4" type="video/mp4">
</video>

<script>

   var purchase_link = 'https://m5stack.com/products/m5stickc-tof-hatvl53l0x';

   anchor_search(purchase_link);
   scrollFunc();

</script>