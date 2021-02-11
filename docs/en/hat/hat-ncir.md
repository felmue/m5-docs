# NCIR HAT

<el-tag effect="plain">SKU:U061</el-tag>

<div class="product_pic"><img src="assets\img\product_pics\hat\ncir_hat\hat_ncir_01.webp"><img src="assets\img\product_pics\hat\ncir_hat\hat_ncir_02.webp"></div>

## Description

**NCIR HAT**  is an M5StickC compatible infrared sensor. Same as M5Unit NCIR, this stickc HAT module Integrates MLX90614 which can be used to measure the surface temperature of a human body or other object. Now that it has a cover of a case of stickc HAT, you can pretty much move all the implementations to stickc-based controller, featured with tiny, low-cost and highly-productization.<br>

Unlike most temperature sensors, this sensor measures infrared light bouncing off of remote objects so it can sense temperature without having to touch them physically. Simply point the sensor towards what you want to measure and it will detect the temperature by absorbing IR waves emitted. Because it doesn't have to touch the object it's measuring, it can sense a wider range of temperatures than most digital sensors! It takes the measurement over a 90-degree field of view so it can be handy for determining the average temperature of an area.<br>

The MLX90614 is factory calibrated in wide temperature ranges: -40 to 125 ˚C for the ambient temperature and -70 to 380 ˚C for the object temperature. 

Connect with M5StickC via GOIO 0/26 (I2C add: 0x5A).<br>

## Product Features

- Operating voltage: 4.5 to 5.5V
- Measuring object temperature range: -70°C ~ 380°C
- Measuring ambient temperature range: -40 to 125 ˚C 
- Measurement accuracy at room temperature: ±0.5°C
- Field of view: 90°
- Software Development Platform: Arduino, UIFlow(Blockly, Python)

## Include

- 1x NCIR HAT

## Applications

-  Body Temperature Measurement
-  Object (biological) Motion Detection

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>Communication protocol</td>
      <td>I2C：0x5A</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>5g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>13g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>24*25*14mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>40*42*30mm</td>
   </tr>
 </table>

### Pin Map

<table>
 <tr><td>M5StickC</td><td>GPIO0</td><td>GPIO26</td><td>3.3V</td><td>GND</td></tr>
 <tr><td>HAT NCIR</td><td>SDA</td><td>SCL</td><td>3.3V</td><td>GND</td></tr>
</table>

## Schematic

<img src="assets\img\product_pics\hat\ncir_hat\hat_ncir_04.webp" width="50%" height="50%">

## Related Link

- **[MLX90614 Datasheet](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/hat/MLX90614-Datasheet-Melexis_en.pdf)**

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_M5StickC_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/HAT/NCIR/EasyLoader_StickC_HAT_NCIR.exe"><el-button type="primary">download EasyLoader</el-button></a>

>1.EasyLoader is a simple and fast program burner. Every product page in EasyLoader provides a product-related case program. It can be burned to the master through simple steps, and a series of function verification can be performed.

>2. After downloading the software, double-click to run the application, connect the M5 device to the computer through the data cable, select the port parameters, click **"Burn"** to start burning. (**For M5StickC burning, please Set the baud rate to 750000 or 115200**)

## Example

### 1. Arduino

[Click here to download Arduino code](https://github.com/m5stack/M5StickC/tree/master/examples/Hat/NCIR_HAT)

### 2. UIFlow

Open http://flow.m5stack.com and Load Demo

<img src="assets\img\product_pics\hat\ncir_hat\ncir.webp">

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/m5stickc-ncir-hatmlx90614';

   anchor_search(purchase_link);
   scrollFunc();

</script>