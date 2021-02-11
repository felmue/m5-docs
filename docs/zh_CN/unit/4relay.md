# 4-Relay {docsify-ignore-all}

<el-tag effect="plain">SKU:U097</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/unit/4_relay/4relay.webp"></div>

## 描述

**4-Relay** 是一款集成4路继电器的Unit，通过I2C进行控制，继电器控制电压最高AC-250V，额定电流10A，瞬时电流可承受16A。每路继电器可单独控制，每路继电器都有一个可编程的状态指示灯。

## 产品特性

- 4路继电器
- AC-250V/10A
- 状态指示灯
- IIC通讯

## 包含

- 1x 4-Relay Unit
- 1x HY2.0-4P线缆(20cm)
- 4x VH3.96-4P接线端子

## 应用

- 直流信号切换
- 数字设备电源通断

## 规格参数
 
<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>最大输入电压</td>
      <td>250V</td>
   </tr>
   <tr>
      <td>额定电流</td>
      <td>10A</td>
   </tr>
   <tr>
      <td>最大瞬时电流</td>
      <td>16A</td>
   </tr>
   <tr>
      <td>通讯方式</td>
      <td>I2C(0x26)</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>40g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>84g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>112*23*18mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>125*65*22mm</td>
   </tr>
 </table>


## EasyLoader

>EasyLoader是一个简洁快速的程序烧录器，其内置了一个产品相关的案例程序，通过简单步骤将其烧录至主控，即可进行一系列的功能验证.**(程序烧录前，请根据设备类型安装相应驱动程序. M5Core型主机[请点击此处查看CP210X驱动安装教程](zh_CN/arduino/arduino_development?id=安装串口驱动)，M5StickC/V/T/ATOM系列可免驱动使用)**

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/UNIT/For%20M5Core/EasyLoader_4_Relay_Unit.exe">Windows</a>
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/MacOS/UNIT/EasyLoader_4Relay_Unit_for_M5Core.dmg">MacOS</a>
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/Unit/4-RELAY_UNIT.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>案例描述:</p>
            <p>A键切换继电器序号，B键切换LED同步/异步，C键控制所有继电器</p>
        </div>
    </div>
</div>

## 原理图

<img src="assets/img/product_pics/unit/4_relay/4-relay_sch.webp">

### 管脚映射

<table>
 <tr><td>M5Core(PORT A)</td><td>SDA(GPIO21)</td><td>SCL(GPIO22)</td><td>5V</td><td>GND</td></tr>
 <tr><td>4-relay Unit</td><td>SDA</td><td>SCL</td><td>5V</td><td>GND</td></tr>
</table>

## 案例程序

### 1. Arduino

- [请点击此处获取Arduino示例程序](https://github.com/m5stack/M5Stack/tree/master/examples/Unit/4-RELAY)

<script>

   var purchase_link = 'https://m5stack.com/products/4-relay-unit';

   anchor_search(purchase_link);
   scrollFunc();

</script>