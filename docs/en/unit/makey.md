# 16-Key Capacitive Touch

<el-tag effect="plain">SKU:U026</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/unit/music/unit_makey_01.webp"></div>

## Description

**16-Key Capacitive Touch Unit** Unit is inspired by an Invention kit called Makey Makey which brings the concept that users can
connect everyday objects to computer programs.

Using a circuit board, alligator clips, and a USB cable, the circuit uses closed loop electrical signals to send the microprocessor either a keyboard stroke or mouse click signal.

We've tried connect a bunch of fruits, one for each key, to this Unit.

When you touch the apple, you make a connection, and MaKey sends the processor a keyboard message. The buzzer inside or speaker on M5core will exhibit the key value, so instead of using a keyboard, you can make a fruit piano.

This Unit communicates with the M5Core via the GROVE A I2C(0x51).

**Instructions:**

1）Use the buzzer on the unit to exhibit sounds:

Take a Dupont wire(male to male), one end plug into GND, hold the other end to your hand.
Take another Dupont wire(male to male), one end plug into different key holes, the other end hold by the other hand. Make it a close circult. Plug into different key tones the buzzer will emit the corresponding tones.

2）Use the speaker on the M5core to exhibit sounds:
connect MAKEY with M5Core via Grove A
Download this [example](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Unit/Makey_NewVersion/Arduino/Makey_new_version).

Repeat the same operation as above. you will see this sound much better.

## Product Features

- Arduino Mega328p Controller
- Buzzer inside
- Up to 16 keys
- Software Development Platform: Arduino, UIFlow (Blockly, Python)
- Two Lego-compatible holes

## Include

- 1x MAKEY unit
- 1x GROVE Cable

## Applications

- Fruit piano

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>Communication protocol</td>
      <td>I2C：0x51</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>7g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>19g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>32*24*8mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>67*53*12mm</td>
   </tr>
 </table>


## Related Link

- **[Maykey Firmware](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Unit/Makey_NewVersion/firmware_328p)**

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Unit/EasyLoader_Makey.exe"><el-button type="primary">download EasyLoader</el-button></a>

>1.EasyLoader is a simple and fast program burner. Every product page in EasyLoader provides a product-related case program. It can be burned to the master through simple steps, and a series of function verification can be performed. .

>2. After downloading the software, double-click to run the application, connect the M5 device to the computer through the data cable, select the port parameters, click **"Burn"** to start burning. (**For M5StickC burning, please Set the baud rate to 750000 or 115200**)

>3. Currently EasyLoader is only suitable for Windows operating system, compatible with M5 system adopts ESP32 as the control core host. Before installing for M5Core, you need to install CP210X driver (you do not need to install with M5StickC as controller)[Click here to view the driver installation tutorial](en/related_documents/M5Burner#install-usb-driver)

## Schematic

<img src="assets/img/product_pics/unit/makey_sch.webp">

### PinMap

<table>
 <tr><td>M5Core(GROVE A)</td><td>GPIO22</td><td>GPIO21</td><td>5V</td><td>GND</td></tr>
 <tr><td>MAKEY Unit</td><td>SCL</td><td>SDA</td><td>5V</td><td>GND</td></tr>
</table>

<img src="assets/img/product_pics/unit/M5GO_Unit_makey_03.webp" width="30%" height="30%">

**Mega328 ISP**Download interface Pin foot definition

<img src="assets\img\product_pics\app\mega328_isp.webp" width="30%" height="30%">

## Example

### 1. Arduino

- [Click here to download the Arduino example](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Unit/Makey_NewVersion/Arduino/Makey_new_version)

<img src="assets/img/product_pics/unit/unit_example/MAKEY/tone_key_pitch_zh_CN.webp">

<img src="assets/img/product_pics/unit/M5GO_Unit_makey_04.webp" width="30%" height="30%">

### 2. UIFlow

- [Click here to download the UIFlow example](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Unit/Makey_NewVersion/UIFlow)

<img src="assets/img/product_pics/unit/unit_example/MAKEY/example_unit_makey_02.webp">

<el-divider content-position="right">Last updated: 2020-12-14</el-divider>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/makey-unit';


   anchor_search(purchase_link);
   scrollFunc();

</script>
