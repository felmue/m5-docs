# DAC

<el-tag effect="plain">SKU:U012</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/unit/dac/unit_dac_01.webp"></div>

## Description

**DAC**, is a unit with the ability to convert digital signal to analog signal (voltage waveform signal) with support for audio waveform and more. It integrates a 12-bit high resolution DAC chip named **MCP4725** which has an on-board non-volatile memory (EEPROM). The unit communicates with the M5Core using the I2C protocol.

The DAC input and configuration data can be programmed to the EEPROM in order for the data to be saved after reboot or system shutdown.

The device I2C address is 0x60 by default unless changed manually.

## Product Features

-  Up to 12 bits of resolution
-  Output 0~3.3V voltage GROVE interface, support [UIFlow](http://flow.m5stack.com) and [Arduino](http://www.arduino.cc)
-  Two Lego-compatible holes

## Include

- 1x DAC Unit
- 1x Grove Cable

## Applications

-  MP3 Audio Player
-  mini Oscilloscope

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>Resolution</td>
      <td>12 bit</td>
   </tr>
   <tr>
      <td>voltage range</td>
      <td>0-3.3V</td>
   </tr>
   <tr>
      <td>Communication protocol</td>
      <td>I2C: 0x60</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>4g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>19g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>32.2*24.2*10.3mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>67*53*12mm</td>
   </tr>
</table>


## Related Link

-  **Datasheet** - [MCP4725](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/unit/MCP4725_en.pdf)


## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Unit/EasyLoader_DAC.exe"><el-button type="primary">download EasyLoader</el-button></a>

>1.EasyLoader is a simple and fast program burner. Every product page in EasyLoader provides a product-related case program. It can be burned to the master through simple steps, and a series of function verification can be performed.

>2. After downloading the software, double-click to run the application, connect the M5 device to the computer through the data cable, select the port parameters, click **"Burn"** to start burning. (**For M5StickC burning, please Set the baud rate to 750000 or 115200**)

>3. Currently EasyLoader is only suitable for Windows operating system, compatible with M5 system adopts ESP32 as the control core host. Before installing for M5Core, you need to install CP210X driver (you do not need to install with M5StickC as controller)[Click here to view the driver installation tutorial](en/related_documents/M5Burner#install-usb-driver)

## Schematic

<img src="assets/img/product_pics/unit/dac_sch.JPG">

### PinMap

<table>
 <tr><td>M5Core(GROVE A)</td><td>GPIO22</td><td>GPIO21</td><td>5V</td><td>GND</td></tr>
 <tr><td>DAC Unit</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

## Example

### 1. Arduino

The code below is incomplete (just for reference). To get the complete code, please click [here](https://github.com/m5stack/M5Stack/tree/master/examples/Unit/DAC_MCP4725)

### 2. UIFlow

- [Click here to download the UIFlow example](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Unit/DAC/UIFlow)

<img src="assets/img/product_pics/unit/dac.webp">

<el-divider content-position="right">Last updated: 2020-12-11</el-divider>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/dac-unit';

   anchor_search(purchase_link);
   scrollFunc();

</script>
