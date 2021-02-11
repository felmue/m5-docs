# FINGER HAT

<el-tag effect="plain">SKU:U074</el-tag>

<div class="product_pic"><img src="assets\img\product_pics\hat\finger_hat\finger_hat_01.webp"><img src="assets\img\product_pics\hat\finger_hat\finger_hat_02.webp"></div>

## 描述

**FINGER Hat**是一款指纹识别传感器. 内部集成 FPC1020SC 电容式指纹识别模组,具备多指纹录入、图像处理、特征值提取、指纹比对、搜索等功能.
采用UART通信协议、紧凑的外观设计、与低功耗能带给项目可靠的安全级别的同时，提供最佳的用户便利性.如果你想要为你的项目添加生物指纹识别功能，并希望其具备稳定可靠的添加、验证、管理机制那么FINGER HAT 是一个不错的解决方案.

UART 参数设置:
- 波特率(默认: 19200bps)
- 起始位(1 bit)
- 停止位(1 bit)
- 校验位(无)

## 产品特性

- 指纹容量:  150
- 采用电容式面阵式半导体指纹传感器
- 传感器每个像素拥有 256 灰度级的像素质量
- 最小存储条件下实现指纹数据的登记及比对：指纹模板为 193 字节
- 1:N 识别 及 1:1 验证功能
- 支持手指 360 旋转识别
- 可适当调节的安全等级 0-9，默认等级 5
- 输出格式:  用户名、图像、特征值
- 特征值大小: 193Byte
- 通讯接口:   UART
- 通讯波特率: 9600-115200（默认为19200）
- 工作温度:   -10° - 60°
- 相对湿度:   20% - 80%

## 包含

- 1x FINGER HAT

## 应用

- 指纹考勤
- 替代密码认证
- 身份识别

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>14g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>26g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>24*65*20mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>75*46*29mm</td>
   </tr>
 </table>

## 原理图

<img src="assets/img/product_pics/hat/finger_hat/finger_hat_04.webp" width="50%" height="50%">

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_M5StickC_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/HAT/EasyLoader_Finger_HAT.exe"><el-button type="primary">点击下载EasyLoader</el-button></a>

>1.EasyLoader是一个简洁快速的程序烧录器，每一个产品页面里的EasyLoader都提供了一个与产品相关的案例程序，通过简单步骤将其烧录至主控，能够进行一系列的功能验证.

>2.下载软件后，双击运行应用程序，将M5设备通过数据线连接至电脑,选择端口参数，点击 **"Burn"** 即可开始烧录.(**为M5StickC烧录时，请将波特率设置在750000或115200**)

## 案例程序

### 2. UIFlow

打开 http://flow.m5stack.com 点击Demo载入UIFlow例程

<img src="assets/img/product_pics/hat/finger_hat/finger.webp">

### 1. Arduino

点击[此处](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Hat/finger-hat/Arduino/FINGER)查看完整示例

## 相关链接

- 通信协议 **[FINGER 串口通信协议](https://github.com/m5stack/M5-Schematic/blob/master/Units/finger/biovo_fingerprint_Protocol_en.DOC)**

- 数据手册 **[FPC1020A](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/hat/1020A_datasheet_cn.pdf)**

## 相关视频

<video class="video_size" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/HAT/FINGER-HAT.mp4" type="video/mp4" >
</video>

<script>

   var purchase_link = 'https://m5stack.com/collections/all/products/m5stickc-fingerprint-hatf1020sc';


   anchor_search(purchase_link);
   scrollFunc();

</script>