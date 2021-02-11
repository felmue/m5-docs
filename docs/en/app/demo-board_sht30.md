# Demo Board (SHT30 VERSION)

<el-tag effect="plain">SKU:K024-B</el-tag>

<div class="product_pic"><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/m5-docs_homepage/app/app_DemoBoard_01.webp"> <img src="assets/img/product_pics/app/Demo-Board/Demo-Board_02.webp"></div>

## Tutorial&Quick-Start

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/Demo-Board_en.pdf"><el-tag effect="plain">Tutorial&PDF</el-tag></a>

## Description

**Demo Board**. This is a feast of IoT stuff, powered by M5Stack. It is an all-in-one Learning board powered by ESP32, which includes anything you can imagine in an IoT + industrial application scenarios. Let's see what you can do with it:  Robotic movement, the most commonly used serial communication port(RS485 RS232), Relay control, all different types of Button control, RF reader, speaker, Microphone and more all able to develope by an M5stack core device, so you can program this board with Blockly(UIFlow), Arduino, and Micropython.  Based on application scenarios, we've partitioned them into different functional parts with the good-looking layout and full-function performance.  Here comes the most powerful IIoT learning board.

## Product Features

- Fully Compatible with the M5Stack stackable and extendable system
- Protoboard, M5-BUS extension
- Each module comes with an individual power switch.
- Environment Sensor set ( Temperature, Humility,  barometric pressure, light intensity, and Microphone )
- Joystick Controller
- 8 Channel of Realy output
- 4x DAC，4x ADC
- 4x4 button matrix
- 8x8 RGB LED matrix
- Encoder
- 1x Servo
- DC-Motor(with feedback encoder)
- step motor with four-phase five-wire
- Radio frequency identification Reader
- RS-485，RS232 series communication


<img src="assets/img/product_pics/app/Demo-Board/Demo-Board_03.webp" width="250" height="250">

## Include

- 1x **Demo Board** learning board
- 1x Power Aapter
- 1x RS232 cable
- 1x RFID Card
- 1x ID Card
- 16x breadboard cable

## Applications

- IOT teaching experiment board
- Multi function test board

<img src="assets/img/product_pics/app/Demo-Board/Demo-Board_04.webp" width="250" height="250">

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>1120g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>1120g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>330*210*95mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>330*210*95mm</td>
   </tr>
 </table>

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Application/Demo%20Board/EasyLoader_APP_Demo_Board.exe"><el-button type="primary">download EasyLoader</el-button></a>

>1.EasyLoader is a simple and fast program burner. Every product page in EasyLoader provides a product-related case program. It can be burned to the master through simple steps, and a series of function verification can be performed.

>2.After downloading the software, double-click to run the application, connect the M5 device to the computer via the data cable, select the port parameters, and click **"Burn"** to start burning.

?>3.The CP210X (USB driver) needs to be installed before the EasyLoader is burned. [Click here to view the driver installation tutorial](en/related_documents/M5Burner#install-usb-driver)

## Module parameters

| **Module Name** | **working Voltage**  |**Patameter** |
| :------: | :------: | :------: |
| ADC | 5V | 4x ADC port/ADS1115 |
| DAC | 5V | 4x DAC port/DAC6574 |
| Joystick | 3.3V | axis-X/Y  potentiometer input, axis-Z button input  |
| SHT30  | 3.3V | I2C address 0x44 |
| BMP280 | 3.3V | I2C address 0x76  |
| Light | 3.3V  | A/D sampling supported, adjustable threshold  |
| Microphone| 3.3V  | A/D sampling supported, adjustable threshold |
| Relay	| 5V  | 8 channels /3A-220V-AC/3A-30V-DC  |
| RGB LED| 5V  | 8x8 LED matrix  |
| Servo  | 5V  |  10KG torsion  |
| DC-Motor | 5V  |  feedback encoder/LV8548MC|
| Stepmotor | 5V | 4-phase 5 wires LV8548MC|
| RFID | 3.3V | Read & Write distance: < 8 cm/ MFRC522 |
| RS485	| 5V  | SP485EEN-L/TR |
| RS232| 5V  | MAX232ESE |
| Encode |  | Encoder button|
| Proto |  | 170x holes |
| Keyboard|   | 4x4 button matrix  |

## Related Link

**Datasheet**

- [ADS1115](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/ads1115_en.pdf)

- [DAC6574](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/dac6574_en.pdf)

- [LV8548MC](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/LV8548MC_en.pdf)

- [TPS54360](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/tps54360_en.pdf)

- [MRC522](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/module/MFRC522_en.pdf)

- [MAX232ESE](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/MAX232ESE_en.pdf)

- [MAX4466](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/application/MAX4466_datasheet_en.pdf)

- [SP485EEN](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/hat/SP485EEN_en.pdf)

- [BMP280](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/hat/BMP280-DS001-11_en.pdf)

- [SHT30](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/unit/SHT3x_Datasheet_digital.pdf)

## Schematic

- [M5IoT-kit](https://github.com/m5stack/M5-Schematic/tree/master/Applications/M5IoT-kit)

## Example

### Arduino IDE

- Click to download [example code](https://github.com/m5stack/DEMO-BOARD)

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-application/products/iot-learning-kit';

   var quickstart_link = 'https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/Demo-Board_en.pdf';

   anchor_search(purchase_link,quickstart_link);
   scrollFunc();

</script>