# Module DC MOTOR

<el-tag effect="plain">SKU:M021</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/module/module_lego_plus_01.webp"></div>

## Description

**DC MOTOR** is built with MEGA328 and L293DD microcontrollers, implemented 4 driver channels. A DC power input is designed for power supplement. Through M-BUS the DC in can automatically power the M5 core at top. DC motor module can drive RJ12 interface encoder-motor easily and quickly, such as LEGO ev3 Motor.（This product is not affiliated with or endorsed by LEGO. LEGO is a trademark of the LEGO Group of companies）

Series Communication: I2C (0x56).

## Product Features

- DC Power input: 6-12V
- DC Connector Type: XT30 (female)
- 4x Motor port
- Compatible with LEGO EV3 motor
- 2x I2C GROVE port (extend PORTA from M5 Core)
- L293DD: PUSH-PULL Driver Chip

## Include

-  1x DC MOTOR module
-  1x 10cm motor cable
-  1x DC connector

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>17g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>48g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>54*54*12mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>95*65*25mm</td>
   </tr>
 </table>

## Related Link

- **[The Firmware of inside MEGA328](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Module/LEGO_PLUS/firmware_328p)**

<!-- ### 1. Arduino IDE -->

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Module/EasyLoader_LEGO_PLUS.exe"><el-button type="primary">download EasyLoader</el-button></a>

>1.EasyLoader is a simple and fast program burner. Every product page in EasyLoader provides a product-related case program. It can be burned to the master through simple steps, and a series of function verification can be performed.

>2.After downloading the software, double-click to run the application, connect the M5 device to the computer via the data cable, select the port parameters, and click **"Burn"** to start burning.

>3.The CP210X (USB driver) needs to be installed before the EasyLoader is burned. [Click here to view the driver installation tutorial](en/related_documents/M5Burner#install-usb-driver)

## PinMap

**Mega328 ISP** Download interface Pin foot definition

<img src="assets\img\product_pics\app\mega328_isp.webp" width="30%" height="30%">

## MBUS PinMap

<img src="assets\img\product_pics\module\module_bus.webp"/>

## Example

### 1. Arduino

To get the complete Arduino code, please click [here](https://github.com/m5stack/M5Stack/tree/master/examples/Modules/LEGO_PLUS)

### 2. UIFlow

To get the complete code, please click [here](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Module/LEGO_PLUS/UIFlow)

<img src="assets/img/product_pics/module/module_example/LEGO_PLUS/example_module_lego_plus_03_en.webp">

## Schematic

<img src="assets/img/product_pics/module/lego_plus_sch.webp">

## NOTE

If you want to change the firmware inside **MEGA328 chip** which has implemented the motor driver code by default, you can overwrite through **ISP** port. Below shows the location of ISP port.

<img src="assets/img/product_pics/module/module_lego_plus_03.webp">

<el-divider content-position="right">Last updated: 2020-12-28</el-divider>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-module/products/lego-module';

   anchor_search(purchase_link);
   scrollFunc();

</script>
