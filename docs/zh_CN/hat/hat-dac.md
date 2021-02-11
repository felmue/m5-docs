# DAC HAT

<el-tag effect="plain">SKU:U068</el-tag>

<div class="product_pic"><img src="assets\img\product_pics\hat\dac_hat\dac_hat_01.webp"><img src="assets\img\product_pics\hat\dac_hat\dac_hat_02.webp"></div>

## 描述

**DAC Hat**是一款兼容M5SticKC的DA转换模块，内部集成DAC转换芯片MCP4725，具备低功耗，高精度，单通道，12位缓冲电压输出数模转换器（DAC），非易失性存储器（EEPROM）.其片上精密输出放大器使其能够达到轨到轨模拟输出摆幅.用户可以使用I2C接口命令将DAC输入和配置烧写到非易失性存储器（EEPROM）中，使得DAC在断电期间仍能保持代码，上电后即可直接使用,I2C地址为0x60.

## 产品特性

- 输出电压: 0-3.3V
- 开发平台: Arduino, UIFlow(Blockly, MicroPython)
- MCP4725: 
    - 12位分辨率
    - 外部A0地址引脚
    - 正常或关断模式
    - 快速稳定时间为6μs（典型值）
    - 外部电压参考（VDD）
    - 轨到轨输出
    - 低功耗
    - 单电源工作：2.7V至5.5V
    - 外部电压参考（VDD）
    - I2C 接口
    - 扩展级温度范围：-40°C至+ 125°C

## 包含

- 1x DAC HAT

## 应用

- 设定点或失调微调
- 传感器校准
- 闭环伺服控制
- 低功耗便携式仪表
- PC外设
- 数据采集系统

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>6g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>19g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>24*25*13mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>67*53*12mm</td>
   </tr>
 </table>

## 原理图

<img src="assets/img/product_pics/hat/dac_hat/dac_hat_04.webp" width="50%" height="50%">

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_M5StickC_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/HAT/ENV/EasyLoader_StickC_HAT_ENV.exe"><el-button type="primary">点击下载EasyLoader</el-button></a>

>1.EasyLoader是一个简洁快速的程序烧录器，每一个产品页面里的EasyLoader都提供了一个与产品相关的案例程序，通过简单步骤将其烧录至主控，能够进行一系列的功能验证.

>2.下载软件后，双击运行应用程序，将M5设备通过数据线连接至电脑,选择端口参数，点击 **"Burn"** 即可开始烧录.(**为M5StickC烧录时，请将波特率设置在750000或115200**)

## 案例程序

### 2. UIFlow

打开 http://flow.m5stack.com 点击Demo载入UIFlow例程

<img src="assets/img/product_pics/hat/dac_hat/dac.webp" width="80%" height="80%">

### 1. Arduino

[点击此处](https://github.com/m5stack/M5StickC/tree/master/examples/Hat/DAC)获取完整程序.

## 相关链接

-  **Datasheet** - [MCP4725](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/hat/MCP4725_en.pdf)

## 相关视频

<video class="video_size" controls>
    <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/HAT/ADC-DAC-HAT.mp4" type="video/mp4" >
</video>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/m5stickc-env-hat';

   anchor_search(purchase_link);
   scrollFunc();

</script>