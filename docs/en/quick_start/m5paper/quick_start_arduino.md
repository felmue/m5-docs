# Arduino IDE Development

## USB Driver

>Before the program is burned, users please download the corresponding CP210X driver package according to the operating system you are using, click the button below. After decompressing the compressed package, select the installation package corresponding to the operating system value for installation.

?>  For Mac OS, make sure System preferences -> Security & Privacy -> General before installing, and allow the apps to be installed from the App Store and identified developers

><img src="/image/base/System_preferences.webp" width="50%">

* __Download CP2104 driver__

<div class="files_download">
   <p class="item">
      <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/drivers/CP210x_VCP_Windows.zip">
      <img src="/image/base/Windows_logo.webp" width="50">
      <span class="item-title">Windows10</span>
      </a>
   </p>

   <p class="item">
      <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/drivers/CP210x_VCP_MacOS.zip">
      <img src="/image/base/MacOS_logo.webp" width="50"> 
      <span class="item-title">MacOS</span>
      </a>
   </p>

   <p class="item">
      <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/drivers/CP210x_VCP_Linux.zip">
      <img src="/image/base/Linux_logo.webp" width="50"> 
      <span class="item-title">Linux</span>
      </a>
   </p>
</div>

><img src="/image/base/CP210X_install.gif " width="70%">


## Arduino-IDE

>[Click here to visit Arduino's official website](https://www.arduino.cc/en/Main/Software),Select the installation package for your own operating system to download.

<img src="assets/img/related_documents/Arduino_IDE/Arduino_install.webp">

## M5Stack Boards Manager

>1.Open up Arduino IDE, navigate to `File`->`Peferences`->`Settings`

<img src="assets/img/related_documents/Arduino_IDE/Arduino_1.webp">

>2.Copy the following M5Stack Boards Manager url to `Additional Boards Manager URLs:`

**https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/arduino/package_m5stack_index.json**

<img src="assets/img/related_documents/Arduino_IDE/arduino_board_config.webp">

>3.Navigate to `Tools`->`Board:`->`Boards Manager...`

<img src="assets/img/related_documents/Arduino_IDE/board_manage.webp">

>4.Search `M5Stack` in the pop-up window, find it and  click `Install`

<img src="assets/img/related_documents/Arduino_IDE/search_M5STACK.webp">

>5.select `Tools`->`Board:`->`M5Stack-Paper`
 
<img src="assets\img\quick_start\m5paper\arduino_01.webp">

>6.select `Sketch`->`Include Library:`->`Manage Libraries` 

<img src="assets/img/related_documents/Arduino_IDE/manage_libraries.webp">

>7.Search `M5EPD` in the pop-up window, find it and  click `Install`  (you can also download and import through Github. [M5EPD-Lib download link](https://github.com/m5stack/M5EPD))

>8.`File`->`Example`->`M5EPD`->`Hello World` Open the example and compile and upload it to the device.

<img src="assets\img\quick_start\m5paper\arduino_03.webp">

## Example

- **Arduino** 

   - [FactoryTest](https://github.com/m5stack/M5Paper_FactoryTest)
   - [M5EPD_Todo](https://github.com/m5stack/M5EPD_Todo)
   - [M5EPD_Calculator](https://github.com/m5stack/M5EPD_Calculator)
   - [M5EPD_TTFExample](https://github.com/m5stack/M5EPD_TTFExample)
   - [M5EPD-Lib](https://github.com/m5stack/M5EPD)

>When using FactoryTest to load special characters (such as Chinese, Japanese), please put the font file into the TF card and name it as `font.ttf`.[download ttf file](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/example/Font.ttf)

-  **API**

   - [Arduino API](en/arduino/arduino_home_page?id=m5paper_api)
   - [image2gray tool](https://github.com/m5stack/M5EPD/tree/main/tools)

<script>

   anchor_search();
   scrollFunc();

</script>