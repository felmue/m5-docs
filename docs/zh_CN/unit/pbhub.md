# PbHUB {docsify-ignore-all}

<el-tag effect="plain">SKU:U041</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/unit/pbhub/pbhub_p1.webp"></div>

## 描述

**PbHUB**, 是一款 GPIO HY2.0-4P PORTB 扩展器,能够将单路 GPIO GROBE 接口拓展至六路.内部集成MEGA328，且搭载驱动程序.不支持多 Unit 嵌套，这意味着无法像**PaHUB**一样挂载多个相同协议、地址的设备.

Port B 中的两条数据总线与ESP32的**GPIO36**和**GPIO26**连接,可根据需求编程配置多个端口的输入(支持模拟输入）、输出.

对于使用电平控制或是模拟值输入的项目，PbHUB 是一个不错的多设备控制的解决方案.

**注意1：编程时请注意通道顺序**

<br>
<img src="assets/img/product_pics/unit/pbhub/pbhub_p3.webp" width="30%" height="30%">
<br>

**注意2: 并非所有带有黑色接口（PortB）的Unit都支持通过PbHUB扩展.PbHUB只能应用于基本的单总线通信，通过I2C协议（内置MEGA328）能够实现基本的数字读写，模拟读写.但对于像Weight（内置HX711）这种通信不仅需要进行anglog读取，还需要依赖于时序的Unit来说，PbHUB无法进行拓展.**

## 产品特性

- GPIO HY2.0-4P PORTB 拓展
- 2x LEGO 兼容孔
- 1-6 拓展

### 包含

- 1x PbHUB Unit
- 1x HY2.0-4P线缆

## 规格参数

<table>
   <tr style="font-weight:bold">
      <td>规格</td>
      <td>参数</td>
   </tr>
   <tr>
      <td>通讯协议</td>
      <td>I2C：0x61(可通过电阻A0，A1，A2修改)</td>
   </tr>
   <tr>
      <td>净重</td>
      <td>7g</td>
   </tr>
   <tr>
      <td>毛重</td>
      <td>19g</td>
   </tr>
   <tr>
      <td>产品尺寸</td>
      <td>48*24*12mm</td>
   </tr>
   <tr>
      <td>包装尺寸</td>
      <td>67*53*12mm</td>
   </tr>
 </table>

## 修改I2C地址

该 Unit 的 I2C 地址为0x61（可通过焊接电阻A0 ~ A2进行更改, 地址范围为0x61 ~ 0x68）.

<img src="assets/img/product_pics/unit/pbhub/pbhub_i2c_addr.webp" width="300px">

<table>
   <tr style="font-weight:bold">
      <td>A0</td>
      <td>A1</td>
      <td>A2</td>
      <td>I2C Address</td>
   </tr>
   <tr>
      <td>/</td>
      <td>/</td>
      <td>/</td>
      <td>0x61</td>
   </tr>
   <tr>
      <td>焊接电阻</td>
      <td>/</td>
      <td>/</td>
      <td>0x62</td>
   </tr>
   <tr>
      <td>/</td>
      <td>焊接电阻</td>
      <td>/</td>
      <td>0x63</td>
   </tr>
   <tr>
      <td>焊接电阻</td>
      <td>焊接电阻</td>
      <td>/</td>
      <td>0x64</td>
   </tr>
   <tr>
      <td>/</td>
      <td>/</td>
      <td>焊接电阻</td>
      <td>0x65</td>
   </tr>
   <tr>
      <td>焊接电阻</td>
      <td>/</td>
      <td>焊接电阻</td>
      <td>0x66</td>
   </tr>
   <tr>
      <td>/</td>
      <td>焊接电阻</td>
      <td>焊接电阻</td>
      <td>0x67</td>
   </tr>
   <tr>
      <td>焊接电阻</td>
      <td>焊接电阻</td>
      <td>焊接电阻</td>
      <td>0x68</td>
   </tr>
 </table>

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Unit/EasyLoader_PbHUB.exe"><el-button type="primary">点击下载EasyLoader</el-button></a>

>1.EasyLoader是一个简洁快速的程序烧录器，每一个产品页面里的EasyLoader都提供了一个与产品相关的案例程序，通过简单步骤将其烧录至主控，能够进行一系列的功能验证.

>2.下载软件后，双击运行应用程序，将M5设备通过数据线连接至电脑,选择端口参数，点击 **"Burn"** 即可开始烧录.(**为M5StickC烧录时，请将波特率设置在750000或115200**)

?>3.目前EasyLoader仅适用于Windows操作系统、兼容M5体系采用ESP32作为控制核心的主机.在为M5Core烧录前需要安装CP210X驱动程序（使用M5StickC作为控制器的则无需安装）[点击此处查看驱动安装教程](zh_CN/related_documents/M5Burner#安装串口驱动)

## 原理图

<img src="assets/img/product_pics/unit/pbhub/pbhub_sch.webp">

## 管脚映射

**Mega328 ISP**下载接口Pin脚定义

<img src="assets\img\product_pics\app\mega328_isp.webp" width="30%" height="30%">

### 驱动协议

## 案例程序

- 测试程序 - **[PbHUB](https://github.com/m5stack/M5Stack/tree/master/examples/Unit/PbHUB)**
- 通讯协议 - I2C
- I2C地址 - 0x61
- Set oneLED Color : LED 地址(2bytes) + RGB 值(3bytes)
- Set moreLED Color : LED 起始地址(2bytes) + LED 结束地址(2bytes) + RGB 值(3bytes)

- [请点击此处获取UIFlow示例](https://github.com/m5stack/M5-ProductExampleCodes/tree/master/Unit/PbHUB/UIFlow)

<img src="assets/img/product_pics/unit/pbhub/pbhub.webp">

<table>
    <tr>
        <td>state</td><td>IO0 Digital Write</td><td>IO1 Digital Write</td><td>IO0 Analog Write</td><td>IO1 Analog Write</td><td>IO0 Digital Read</td><td>IO1 Digital Read</td><td>IO0 Analog Read</td><td>reserve</td><td>Set RGB LED Num</td><td>Set oneLED Color*</td><td>Set moreLED Color*</td><td>Set Brightness</td>
    </tr>
    <tr>
        <td>r/w</td></td></td><td>w</td><td>w</td><td>w</td><td>w</td><td>r</td><td>r</td><td>r</td><td>r</td><td>w</td><td>w</td><td>w</td><td>w</td></tr>
    <tr>
        <td>data length (Byte)</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>2</td><td>/</td><td>2</td><td>5</td><td>7</td><td>1</td>
    </tr>
    <tr>
        <td>ch0 cmd</td></td><td>40</td><td>41</td><td>42</td><td>43</td><td>44</td><td>45</td><td>46</td><td>47</td><td>48</td><td>49</td><td>4A</td><td>4B</td>
    </tr>
    <tr>
        <td>ch1 cmd</td></td><td>50</td><td>51</td><td>52</td><td>53</td><td>54</td><td>55</td><td>56</td><td>57</td><td>58</td><td>59</td><td>5A</td><td>5B</td>
    </tr>
    <tr>
        <td>ch2 cmd</td></td><td>60</td><td>61</td><td>62</td><td>63</td><td>64</td><td>65</td><td>46</td><td>67</td><td>68</td><td>69</td><td>6A</td><td>6B</td>
    </tr>
    <tr>
       <td>ch3 cmd</td></td><td>70</td><td>71</td><td>72</td><td>73</td><td>74</td><td>75</td><td>76</td><td>77</td><td>78</td><td>79</td><td>7A</td><td>7B</td>
    </tr>
    <tr>
        <td>ch4 cmd</td></td><td>80</td><td>81</td><td>82</td><td>83</td><td>84</td><td>85</td><td>86</td><td>87</td><td>88</td><td>89</td><td>8A</td><td>8B</td>
    </tr>
    <tr>
       <td>ch5 cmd</td></td><td>A0</td><td>A1</td><td>A2</td><td>A3</td><td>A4</td><td>A5</td><td>A6</td><td>A7</td><td>A8</td><td>A9</td><td>AA</td><td>AB</td>
    </tr>

</table>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/pb-hub';

   anchor_search(purchase_link);
   scrollFunc();

</script>