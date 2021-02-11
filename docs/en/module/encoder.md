# Module ENCODER

<el-tag effect="plain">SKU:A006</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/module/module_encoder_01.webp"><img src="assets/img/product_pics/module/module_encoder_02.webp"></div>

## Description

**ENCODER** is compatible with FACE Kit. You can have it replace the key-card panel inside the FACE kit. It is designed for rotary encoder control, integrated Mega328 microprocessor inside and LEDs around the encoder.

The series communication protocol between M5 core and ENCODER is I2C (The default I2c address is: 0x5E)

<img src="assets/img/product_pics/module/module_encoder_03.webp" width="60%" height="60%">

## Product Features

-  12 RGB Led
-  I2C communication
-  Simple API for programming
-  Mega328 inside
-  Encoder detection

## Include

-  1x M5Stack ENCODER Module

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>RGB LED</td>
      <td>x12</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>27g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>47g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>58.2*54.2*28mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>95*65*25mm</td>
   </tr>
   <tr>
      <td>Material</td>
      <td>Plastic(PC)</td>
   </tr>
</table>


## EasyLoader

>EasyLoader is a concise and fast program writer, which has a built-in case program related to the product. It can be burned to the main control by simple steps to perform a series of function verification. Please install the corresponding driver according to the device type. M5Core host [Please click here to view the CP210X driver installation tutorial](en/arduino/arduino_development), M5StickC/V/T/ATOM series can be used without driver)

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/MODULE/EasyLoader_FACES_Encoder.exe">Windows</a>
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/MacOS/MODULE/EasyLoader_FACES_Encoder_0x1000.dmg">MacOS</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/Module/FACES_ENCODER.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>Description:</p>
            <p>Display encoder count and button status, left turn decrease right turn increase.</p>
        </div>
    </div>
</div>

## Function

**Control single RGB**

```arduino
/*
    Parameter:
        led_index: 0 ~ 11
        r, g, b: 0 ~ 254
*/
void Led(int led_index, int r, int g, int b){
    // I2C send data
    Wire.beginTransmission(Faces_Encoder_I2C_ADDR);
    Wire.write(led_index);
    Wire.write(r);
    Wire.write(g);
    Wire.write(b);
    Wire.endTransmission();
}
```

**Read encoder increment**

```arduino
void get_encoder_increment(void){
    int temp_encoder_increment;

    // I2C read data
    Wire.requestFrom(Faces_Encoder_I2C_ADDR, 3);
    if(Wire.available()){
       temp_encoder_increment = Wire.read();// get increment
       button_state = Wire.read();// get button value
    }
    if(temp_encoder_increment > 127){//anti-clockwise
        direction = 1;// flag for encoder direction
        encoder_increment = 256 - temp_encoder_increment;
    }
    else{// clockwise
        direction = 0;
        encoder_increment = temp_encoder_increment;
    }
}
```

## Related Link

- **[The Firmware of inside MEGA328](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Module/ENCODER/firmware_328p/FacesEncoder328)**

## PinMap

**Mega328 ISP**Download interface Pin foot definition

<img src="assets\img\product_pics\app\mega328_isp.webp" width="30%" height="30%">

## Example

### 1. Arduino IDE

If you want the complete code `faces_encoder.ino`, please click [here](https://github.com/m5stack/M5Stack/tree/master/examples/Face/ENCODER)


<img src="assets/img/product_pics/module/module_example/ENCODER/example_faces_encoder_01.webp" width="55%" height="55%">

### 2. UIFlow

<img src="assets/img/product_pics/module/module_example/ENCODER/encoder.webp" >

<el-divider content-position="right">Last updated: 2020-12-24</el-divider>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-module/products/encoder-module';

   anchor_search(purchase_link);
   scrollFunc();

</script>
