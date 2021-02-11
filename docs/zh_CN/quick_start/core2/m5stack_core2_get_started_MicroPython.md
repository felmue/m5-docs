# UIFlow 快速上手

?>本教程适用于M5Core2

## 驱动安装

>程序烧录前，M5Core2用户请根据您使用的操作系统，点击下方按钮下载相应的CP210X驱动程序压缩包.在解压压缩包后，选择对应操作系统位数的安装包进行安装。

* __下载CP210X驱动程序__

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


## 烧录工具

>请根据您所使用的操作系统，点击下方按钮下载相应的M5Burner固件烧录工具.解压打开应用程序。

<div class="files_download">
   <p class="item">
      <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/software/M5Burner.zip">
      <img src="/image/base/Windows_logo.webp" width="50">
      <span class="item-title">Windows10</span>
      </a>
   </p>

   <p class="item">
      <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/software/M5Burner_MacOS.zip">
      <img src="/image/base/MacOS_logo.webp" width="50"> 
      <span class="item-title">MacOS</span>
      </a>
   </p>

   <p class="item">
      <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/software/M5Burner_Linux.zip">
      <img src="/image/base/Linux_logo.webp" width="50"> 
      <span class="item-title">Linux</span>
      </a>
   </p>
</div>


<img src="assets/img/getting_started_pics/how_to_burn_firmware/M5Burner/M5Burner_01.webp">

?>注意：MacOS用户安装完成后请将应用放入Application文件夹内，如下图所示。

><img src="/image/base/application.webp" width="70%"> 

?>注意：Linux用户请切换至解压文件路径下，在终端中运行`./M5Burner`, 运行应用。

## 固件烧录

>1.双击打开Burner烧录工具，①在左侧菜单中选择对应的设备类型，②选择你所需要的固件版本，③点击下载按钮进行下载。

<img src="assets\img\quick_start\core2\burner_m5core01.webp" width="70%">

>2.然后将M5设备通过Type-C数据线连接到电脑，选择对应的COM口，波特率可使用M5Burner中的默认配置，④点击右侧Erase擦除Flash，完成后关闭当前页面。⑤点击"Burn"开始烧录，在烧录时可填入WIFI配置信息。

<img src="assets\img\quick_start\core2\burner_m5core02.webp" width="70%">

>3.当烧录日志提示`Burn Successfully`时，则表示固件已经烧录完成。

<img src="assets\img\quick_start\core2\burner_m5core04.webp" width="70%">

>4. 如果您需要修改配置文件，⑥可点击configuration进行修改。

<img src="assets\img\quick_start\core2\burner_m5core05.webp" width="70%">


?>首次烧录或固件程序运行异常时，可点击右上角的"Erase"擦除flash内存，在后续的固件更新时，则无需再次擦除，否则将删除已保存的Wi-Fi信息且刷新API Key.


## 配置WIFI

>UIFlow提供了离线与web版本的编程器，在使用web版本的UIFlow时，我们需要为设备配置WiFi连接。下面介绍为设备配置WiFi连接的两种方式（烧录配置与AP热点配置）。


### 烧录配置WiFi(推荐)

?>M5Burner支持WiFi连接的前期烧录配置, 用户只需在固件烧录前将WiFi信息填入WiFi配置框，填入的WiFi信息将随同固件一起烧录保存至M5设备。

<img src="assets/img/quick_start/core2/burner_wifi.webp" width="70%">


### AP热点配置WiFi

>1.单击设备左侧的电源键开机，屏幕出现UIFlow Logo，等待进入主页面后，按下屏幕上"Setup"按钮。在`WiFi`选项中，按下config Wi-Fi by web选项的start按钮，设备会自动重启，其中Secelt Wi-Fi为上次连接的WiFi。设备跳转后将显示WiFi Config页面，按照提示通过手机或电脑的WiFi连接SSID热点，打开浏览器访问 __192.168.4.1__，在弹出的页面内输入WiFi信息进行配置即可成功配网。配置成功后设备将自动重启。并进入编程模式。

<img src="assets\img\quick_start\core2\core_ap_setup.webp">

?>注意：配置的WiFi信息中，不允许出现"空格"等特殊字符。

<img src="assets\img\getting_started_pics\m5stack_core\get_started_with_uiflow\uiflow_wifi_setup2.webp">


## 网络编程模式与API KEY

#### 进入网络编程模式

?>网络编程模式是M5设备与UIFlow web编程平台的一个对接模式,屏幕会显示出当前设备的网络连接状态。当页面左上角的WiFi与云端连接指示标志为绿色时，则代表随时可接收程序推送。默认情况下，在首次WiFi网络配置成功后，设备将自动重启，并进入网络编程模式。若您在运行其他应用后不知如何重新进入编程模式，你可以参考以下操作。

>开机后，在屏幕出现菜单后迅速按下屏幕中间Flow按键进入API KEY页面，使用电脑浏览器访问[flow.m5stack.com](http://flow.m5stack.com/)进入UIFlow编程页面.

<img src="assets\img\quick_start\core2\core_wifi_mode.webp">


#### API KEY配对

>API KEY是M5设备在使用UIFlow web编程时的通信凭证。通过在UIFlow端配置相应的API KEY，能够为指定的设备推送程序。用户需在电脑端浏览器访问[flow.m5stack.com](http://flow.m5stack.com/)进入UIFlow编程页面，点击页面右上角的菜单栏中的设置按钮，输入对应设备上的API Key，选择使用的硬件，点击OK保存，等待提示连接成功。

<img src="assets/img/quick_start/core2/uiflow_apikey.webp">

## Hello M5
 
>完成以上步骤，就可以开始使用UIFlow进行编程了。（1. 放置标签  2. 添加标签程序块 .3 点击右上角运行按钮 ）

<img src="assets/img/quick_start/core2/uiflow_use.gif">

## UIFlow Desktop IDE
 
>当使用离线版UIFlow进行编程时，需要将设备配置为`USB模式`。（1. 启动设备  2. 点击UIFlow选项 .3 选择USB模式 ）

<img src="assets\img\quick_start\core2\core_usb_mode.webp">


## 相关链接

- [UIFlow Block介绍](zh_CN/uiflow/uiflow_home_page)

<script>
   anchor_search();
   scrollFunc();
</script>
