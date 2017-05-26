# 3DPringtingRelated
==========================
## 3D 打印技术报告
---


### 1、历史

### 2、常见3D技术分类

### 3、主流3D打印机结构
> &#160;&#160;&#160;&#160;&#160;&#160;**3D打印机有两种主流结构，以Kossel为代表的并联臂型、也叫Delta型、三角洲型，和以Makerbot、Prusa为代表的XYZ型，也叫cartesian型、笛卡尔型。还有比较少见的机械臂型和五轴加工中心型。下面将以上述两种主流结构及其分支进行介绍。**
#### 3.1 三角架型结构
<img src="https://ooo.0o0.ooo/2017/05/25/5926950196ac0.jpg" alt="三角架型-Reprappro-huxley.jpg" title="三角架型-Reprappro-huxley.jpg" width="200" height="200" align=center />
[图1 三角架型-Reprappro-huxley](http://reprap.org/wiki/RepRapPro_Huxley)
<img src="https://ooo.0o0.ooo/2017/05/25/5926bd85b3db0.jpg" alt="三角架型-prusa-mendel.jpg" title="三角架型-prusa-mendel.jpg" width="200" height="200" align=center />
[图2 三角架型-prusa-mendel](http://reprap.org/wiki/Prusa_Mendel)


#### 3.2 矩形盒式结构


#### 3.3 矩形杆式结构
<img src="https://ooo.0o0.ooo/2017/05/25/5926bc9b0f8b6.jpg" alt="矩形杆式-Prusai3-metalframe.jpg" title="矩形杆式-Prusai3-metalframe.jpg" width="200" height="200" align=center />
[图3 矩形杆式-Prusai3-metalframe](http://reprap.org/wiki/Prusa_i3/zh_cn)
&#160;&#160;&#160;&#160;&#160;&#160;这种结构采用了激光切割技术机身组装精度可以跟盒式结构媲美，又继承了三角形结构的的结构简单，其XYZ轴的运动方式与三角形结构的运动方式是一致的，所以也同时继承了三角形结构的缺点。杆式结构的Z轴步进电机放在机身的底部，由于杆式结构与工作平台的接触面积较小，所以将较重的步进电机放在底部以降低中心。
##### **优点**：
1. 结构简单，组装、维修等都较为方便
2. 整机成本较低
##### **缺点**：
1. 打印时，打印物体随热床在Y轴前后移动
2. 电源、控制板放的位置比较随意裸露
#### 3.4 三角爪式结构(Delta型)
<img src="https://ooo.0o0.ooo/2017/05/25/592667079749b.jpg" alt="delta 450px-Rostock.jpg" title="delta 450px-Rostock.jpg" width="200" height="200" align=center />
[图4 Delta-Rostock](http://reprap.org/wiki/Rostock)
&#160;&#160;&#160;&#160;&#160;&#160;这种结构是开源3d打印机的一个重要分支，其数学原理实际上还是笛卡尔坐标系，只是通过三角函数将XY坐标映射到三台垂直的轴上去，这种结构的有对喷头的重量有较高的要求，因此通常采用J-head 和 齿轮式挤出机的。这种结构的机械复杂程度要比传统的直角坐标系结构简单很多，但是固件就复杂多了。现在Marlin固件有一个专门的分支来控制这类型的3d打印机。这种结构有一个很大的不足就是Z轴方向的体积较大（因为要容纳爪的长度），构建高度20CM的打印机整体高度可以达到40-50CM，所以这种结构适合在有固定场所使用。
##### **优点**：
1. 打印精度、打印速度较高
2. 安装过程较为简单、维修也较为简单
##### **缺点**：
1. 初期固件调试复杂，需要保持喷头平稳
2. 整机体积较大，上层浪费过多安装喷头的空间

### 4、相关网站
#### 4.1 整体项目开源
 1. [**Marlin 3D Printer Firmware**](https://github.com/MarlinFirmware/Marlin)
 2. [**David Crocker's Solutions**](https://miscsolutions.wordpress.com/)
 3. [**RepRap Wiki**](http://reprap.org/wiki/Main_Page)
 4. [**Ultimaker 3D printers**](https://ultimaker.com/en/resources/manuals/ultimaker-3d-printers)
 5. [**LULZBOT**](https://www.lulzbot.com/)
#### 4.2 软件部分开源
 1. [**NanoDLP**](https://www.nanodlp.com/) 
 2. [**MatterControl | 3D Printing Software**](https://github.com/MatterHackers/MatterControl)
#### 4.3 相关3D打印公司
1. [**Printrbot**](http://printrbot.com/)
2. [**MakeBot**](https://www.makerbot.com/)
 

