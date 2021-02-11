# TRACE

<el-tag effect="plain">SKU:A048</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/unit/unit_trace_01.webp"></div>


## 描述

**TRACE** 是一款红外巡线 Unit.内置4组红外发光LED和红外敏感光电晶体管,机器人在进行移动的同时能够实时的检测地面背景颜色，并其转化为数字信号输出到微控制器.通过程序进行路线矫正，实现巡线功能.该 Unit 与 M5Core 通过 PORT A 接口通信，I2C 地址为**0x5A**.

<img src="assets/img/product_pics/unit/unit_trace_02.webp" width="30%" height="30%">

## 产品特性

- 工作范围：反射面距光电面小于11mm
- HY2.0-4P 接口, 支持 [UIFlow](http://flow.m5stack.com) 、 [Arduino](http://www.arduino.cc)
- 2x LEGO 兼容孔

## 包含

- 1x TRACE Unit

## 应用

- 巡线机器人

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>32g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>34g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>70*16*18mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>200*100*10mm</td>
   </tr>
 </table>

## 相关链接

- **[MEGA328 内部固件](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Unit/TRACE/firmware_328p)**

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Unit/EasyLoader_TRACE.exe"><el-button type="primary">点击下载EasyLoader</el-button></a>

>1.EasyLoader是一个简洁快速的程序烧录器，每一个产品页面里的EasyLoader都提供了一个与产品相关的案例程序，通过简单步骤将其烧录至主控，能够进行一系列的功能验证.

>2.下载软件后，双击运行应用程序，将M5设备通过数据线连接至电脑,选择端口参数，点击 **"Burn"** 即可开始烧录.(**为M5StickC烧录时，请将波特率设置在750000或115200**)

?>3.目前EasyLoader仅适用于Windows操作系统、兼容M5体系采用ESP32作为控制核心的主机.在为M5Core烧录前需要安装CP210X驱动程序（使用M5StickC作为控制器的则无需安装）[点击此处查看驱动安装教程](zh_CN/related_documents/M5Burner#安装串口驱动)

## 管脚映射

**Mega328 ISP**下载接口Pin脚定义

<img src="assets\img\product_pics\app\mega328_isp.webp" width="30%" height="30%">


## 案例程序

### 1. Arduino

- [请点击此处获取Arduino示例程序](https://github.com/m5stack/M5Stack/tree/master/examples/Unit/TRACE)

<img src="assets/img/product_pics/unit/unit_trace_04.webp">

### 2. UIFlow

- [请点击此处获取UIFlow示例](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Unit/TRACE/UIFlow)

<img src="assets/img/product_pics/unit/unit_example/TRACE/example_unit_trace_01.webp">

## 原理图

<img src="assets/img/product_pics/unit/trace_sch.webp">

### 管脚映射

<table>
 <tr><td>M5Core(PORT A)</td><td>GPIO22</td><td>GPIO21</td><td>5V</td><td>GND</td></tr>
 <tr><td>TRACE Unit</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/m5stack-trace-board-for-lidar-bot';

   anchor_search(purchase_link);
   scrollFunc();

</script>