# **Android学习笔记**

## 第一章  Android概述

- ### 知识点

1. Android是什么

   Android(安卓)是一种基于**Linux内核**的**开放源代码**的**操作系统**      

2. Android操作系统的体系结构

- 应用程序层
- 应用程序程序框架层
- 系统库和Android运行时
- Linux内核



​	3.Android开发平台和语言

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/F8F3A8F5DC8F4F48AFEBCE8715EFFB10/48)

​	4.Android四大组件

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/158FA3ED23664A26A701B6921672408D/51)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/811619BE38B54DFDB3A0FA0707BEC7A7/53)

​	5.作业

1. Android是基于___Linux___的开源操作系统
2. Android操作系统的体系结构分为哪四层？

​      –应用程序层

​       –应用程序程序框架层

​       –系统库和Android运行时

​        –Linux内核

3.在Android系统的体系结构中，Android运行时的Dalvik虚拟机和ART模式有什么区别？

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/11959CD73B8F427EB4C5DD01667C1D8B/66)

4.目前主流的Android App开发语言是__Java____？2017年Google宣布___Kotlin_____语言将成为新的主流开发语言？

5.Android开发存在的兼容性问题主要表现在哪几方面？

- Android API版本多，目前市场上仍在使用的有10多种；

- Android屏幕分辨率众多，开发时需考虑屏幕适配问题；

- Android厂家、产品众多，硬件设备各不相同，同一款App不一定在所  有手机上都能正常运行。

## **第二章 Android开发环境**

1. JDK安装

![image-1](..\img\image-1.jpg)

2.SDK

![image-2](..\img\image-2.jpg)

3.AVD

![image-3](..\img\image-3.jpg)

## **第三章 Android应用技术基础**

**创建运行和调试一个项目**

 创建

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/F718C5148432491684C6761C04207BBF/226" alt="img" style="zoom:33%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/24C09D2BB8C04552B270C3607F9EB078/218" alt="img" style="zoom:33%;" />

运行

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/50CBA72ED83F48EF9FFCCD50CB8958D4/230" alt="img" style="zoom:33%;" />

选择 Cold Boot Now

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/BD5434BC54F94BD3AA5B862E1F440622/221" alt="img" style="zoom:33%;" />

调试

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/E01C29F88C514C61A7A9C568E3B803B2/289" alt="img" style="zoom:33%;" />

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/3C17774E0D21433AA7424C25EA5FDA67/321)

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/99078352D32545B9A589697E3D2382B8/324" alt="img" style="zoom:33%;" />

**Android项目结构**

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/AA710A5149F94EA48624318521C97ABF/238" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/ABFF5D1B29CB4FFFA6BE3ADC1F754364/241" alt="img" style="zoom:50%;" />

**Gradle**

第三方自动化构建工具，依赖管理、编译、测试、打包、部署、发布…

查看和修改Gradle插件和Gradle版本：

①界面修改

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/7A3E3C1D73FD4F74AED1F558C25F3E13/251" alt="img" style="zoom:50%;" />

②文档修改

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/7A2D213BBBA8477CBDDE85FD2B23B0D2/259" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/7AC4ACA530DC481FA797D9D0C3320A03/266" alt="img" style="zoom:50%;" />

更新Gradle和Gradle插件*(以下二选一)*

–联网更新（国内网络更新速度缓慢）

–手动下载更新相关版本Gradle

•https://blog.csdn.net/qq_36518248/article/details/89366584

Gradle文件

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/5A6B9BC4D6E04DE09CE87CDE79AB07BF/264" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/5E4DE53890934C1EBC81F59E81A78B78/268" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/CC6F09E910B44AEF824E978BBEE307BB/271" alt="img" style="zoom:50%;" />

**Android SDK**

Android开发包，包含了Android开发的API、工具、文档

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/AD30848289BF44B7A8AE91DCBD9650D9/281" alt="img" style="zoom:50%;" />

SDK更新

–打开SDK Manager

–[https://www.cnblogs.com/kangjianwei101/p/5621238.html#m4](https://www.cnblogs.com/kangjianwei101/p/5621238.html) -> “4.Android SDK Manager使用”

**abd**

abd命令：

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/0236E81597494F4BAAB3B9C9A1FE1F07/303)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/A8D08F7CEC6341EE993B5FCF1CAFCCCA/306)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/61BC75CAEB064CE8B86516A12BD19698/309)

**作业**

1、以下参数分别代表什么意思？

​    minSDKVersion：应用兼容的最低SDK版本

​    targetSDKVersion：最高级别的SDK版本

​    compileSDKVersion：AS编译APK使用SDK版本

2、AndroidManifest.xml文件的作用是？

   作为整个Android应用的入口，是每个app都有唯一一个该文件，是app的清单文件，包含声明组件和声明权限，Manifest.xml 描述了package中暴露的组件，他们各自的实现类，各种能被处理的数据和启动位置。出了四大组件的声明，还指定了app的一些权限和安全控制和测试。

3、Gradle的作用是什么？

   gradle 是一个构建工具, 为gradle指定规则, 构建app, 包括编译、打包。

4、build.gradle文件中，dependencies包含哪几种类型依赖？

   

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/EF77F8E7E0004AD6A676234FEC2EF2AA/329)

5、adb工具的作用是什么？

   abd命令可以查看设备、安装软件、卸载软件、登陆设备等。

## **第四章 界面编程**

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/D40A71EB05AE46BFAAD5E733321BF4AE/342)

### **UI编程基础**

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/FFBABF4EE8A74787BAB2081640BE7E25/346)

#### **1、常用控件**

​      文本控件：– TextView – EditText 

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/78328C313B5247A79712149E3C72E7C3/355)

​    

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/70128E22BE744A8D87D20BC32FBD1623/361)

​      图片控件：– ImageView 

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/8C7791FA42FA493EB863BB29D9184401/358)

​      按钮控件： – Button – ImageButton 

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/4C046691BE8D49FC8BACBC0AF74AED5B/364)

​      状态开关按钮：– ToggleButton 

​      单选与复选按钮：– CheckBox和RadioButton 

​      时钟控件：– AnalogClock – DigitalClock

​      日期与时间选择控件： – DatePicker – TimePicker

#### **2、常用布局**

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/21E73E89D61C4690BD00B43785F7EA99/370)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/FE985241EB0348668552612AF6FD9B1E/383)

#### **3、事件处理**

​     基于监听器的事件处理

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/EEF5C6F670FC43F683DF9F94B4D89DCD/390)

### **UI编程拓展**

#### **1、对话框开发**

​      简单对话框

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/CF43494566F9442DBB85CF9581191972/405)

​    简单列表对话框

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/355B952472684F449F1639CF7420BB06/407)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/14A96EFDB90A4562B18D2BAA9075C8AE/413)

   自定义对话框

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/93D17C5F00C74C41B17FB55A6C6FE446/417)

#### **2、菜单开发**

OptionMenu界面开发

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/254C06246CC7437285CA7B23DAF422C8/426)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/E0E028D9065E4D88A039BE18F4B293FF/428)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/91F4BF5C3DEA4AAA99D0468E2C70E1E3/431)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/118B5E64CBDC44E6B0984D3DEF673B1E/433)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/A5289A00259748EEA773C5F897E53E64/436)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/BA779EDA0CF841FD9DCA3C247186EB4E/439)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/192D83CA4D724CE4BE2118CF9FB45000/441)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/548D2D3BBCE24549B13C13D94038667B/443)

OpeanMenu事件处理

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/0AB668A533DA4B2185810A362AD27005/448)

上下文菜单

​       界面开发（第五步与OpeanMenu不同）

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/3D1FAB0F3B0443AC8F74C5D59115F8FA/454)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/9D7BC95ED8C1415FBC73D2D1DAEE9F68/456)

​     

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/24286358C62540A79BBBFAB065AC4687/460)

​      事件处理

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/EF1CB0087C88429C80F5DFA2714A10A6/462)

#### **3、导航界面开发**

编码实现

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/CBA9622986BF420F85F24E8EE7602052/467)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/13E848573B514DAAA2E7F2FA8B120298/469)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/9C4EEFEAF19C45D3A833F89E339356BE/472)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/AF5AB19BCD6A4DBD93CA613D5834251A/474)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/0ED9CB2E1F114E8EB47C1371CD332356/477)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/6E6A8521855A417694D128AE10348420/479)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/2A04BE35E8D94269A09C36C77C37DB77/482)

### **UI动态编程**

#### **1、ListView和Adapter**

​      ListView界面开发

​        实现原理：

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/D451AB2D07D24D578055552026F730C2/499)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/BF86E8D4035E4B7B942BAE919DA23662/501)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/3FBDF15E1F9349429A1493BF5C0B56A7/504)

​        编码实现

- ArrayAdapter<T>实现简单列表项页面

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/A524A820B024475D8B7814A77170AD63/512)

​     

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/512CDB1481E04EF2B733362EE99BA7B5/515)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/E34855891B1D4C22AD3FCE90ADB4DC71/517)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/3C83AB2718D34C6E8420B7E4367C9668/520)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/0B294A1760864162AF5BBFBAF67BFB37/522)

- SimpleAdapter实现复杂列表项页面

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/31E659538F05402C9801180B658B135B/527)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/4025FA5AD8CF43E19E6FBBBAF84085AF/530)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/3503E9068905476AA2D9945749995A04/532)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/96EF2F8FD39B4EB59DAFC89CEE85128B/534)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/6E81E9B00329431CAA70E4EC37A5D05C/536)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/FDBFC3E9AED0447D86C21DC4ACF9BD29/539)

- 自定义Adapter实现复杂列表项页面

​            第四步与前面不同

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/47B18116EACF4884BFA375A2BCF474EE/547)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/A55B8BEE2DF846B98E8C116DDC870B3F/550)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/9B012320606E46FCBFCA99AB5D01DFE0/553)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/AED9B4BCD345400B9C3A1D2B59C80DA4/555)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/C230E3D8AB284CE18566D6F48AFE4135/557)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/C2FF79F1656A4FC68DC8DE54D66FE1CB/559)

- 自定义Adapter性能优化

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/46B1AD1C61454C8684B5A45C3401913B/564)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/E8E269079F84497FBF6EAA78E749EF75/566)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/19721DF943A6486984C7C65DDE270926/568)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/579D160DE7194C42989BEA5444A5D66E/571)

2、事件处理

- Click事件处理

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/103F0945B640453D9A7D447AFC9324E4/576)

- 长按事件处理

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/679D5389B9D548E6B8CFA38F1D8AA8B3/581)

- 修改并刷新页面

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/3C7A1AEA9EE041FAB7B7551F445FFC99/585)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/35987F973F7F4DBBAC8B2E93C9620B39/588)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/D53F7196209247E5A48C0BCAC55F5254/592)

#### **2、RecyclerView**

界面开发

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/4E4956E8A77F4D1C87FF8D5A7C31CA82/598)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/B6DF4B83E822433E9B19C9F8EF140C91/600)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/268C59CADC9547A389ED02C21FB65DAE/602)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/A6B739CD7F6A436396C35F545E6B3FF9/605)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/76FF4FD4089543E8913E90A4ED338DA4/608)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/7B2184D9B3AB4356809783201D7F05C3/610)

#### **3、AdapterView类**

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/E449996F0564453387045932EF6AAE4C/616)

**作业**

1、列举常用的几个控件和布局。

​	<u>五大布局：</u>

   	<u>（1）LinaerLayout</u>

   	<u>（2）RelativeLayout</u>  

   	<u>（3）FrameLayout</u> 

   	<u>（4）AbsoluteLayout</u> 

   	<u>（5）TableLayout</u> 



2、所有控件和布局都继承自哪个类？

​	<u>View类</u>



3、属性layout_width和layout_height取值有哪几种？

<u>android:layout_height：指定该子组件的布局高度；</u> 

<u>android:layout_width：指定该子组件的布局宽度；</u> 

<u>他们分别支持3种属性值，match_parent,fill_parent,wrap_content。match_parent：指定子组件的高度、宽度与父容器组件的高度、宽度相同。</u> 

<u>fill_parent：作用与match_parent相同，已被match_parent取代。</u> 

<u>wrap_content：指定子组件的大小刚好能包裹它的内容。</u>



4、布局文件放在哪个文件夹？图片放在哪个文件夹？

<u>layout                    drawable</u>



5、尺寸的单位是什么？文字尺寸用哪个单位？为什么？

<u>px：表示屏幕实际的象素。例如，320*480的屏幕在横向有320个象素，在纵向有480个象素。</u>

<u>pt：表示一个点，是屏幕的物理尺寸。大小为1英寸的1/72。</u>

<u>in：表示英寸，是屏幕的物理尺寸。每英寸等于2.54厘米。例如，形容手机屏幕大小，经常说，3.2（英）寸、3.5（英）寸、4（英）寸就是指这个单位。这些尺寸是屏幕的对角线长度。如果手机的屏幕是3.2英寸，表示手机的屏幕（可视区域）对角线长度是3.2*2.54 = 8.128厘米。读者可以去量一量自己的手机屏幕，看和实际的尺寸是否一致。</u>

<u>mm：表示毫米，是屏幕的物理尺寸。</u>



6、事件处理方式有哪几种？

<u>android的事件处理机制有两种：一种是基于回调的，一种基于事件监听的。</u>



## **第五章 Activity活动**

### **1.Activity是什么**

<u>–肉眼可见的，与用户交互的界面，包括手机桌面</u>

<u>–每个界面都与一个Activity一一对应</u>

<u>–作用：展示界面，并与用户交互</u>

<u>–展示型组件，对用户来说，Activity几乎是一个应用的全部</u>



### **2.Activity的创建和注册**

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/2883B2548D924F47A159B56417DA5E42/683)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/07F108AA61974B8EAA053D434F47FEA3/685)

### 3.**Activity的启动**

​	**1、第一个Activity的启动**

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/CFE34A8750EB4C168770ABF9BBE8FFBC/693)

**2、其他Activity的的启动**

​       **startactivity()启动**

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/789A9F88F3EE4DFFAA6445B5BF11ABE3/699" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/2EFA1EC41C2C490B95BE151D24C59834/702" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/89860D8A686B4349B19DA818C8CD38BA/704" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/E6471C7D680042609A9323EBEC248FD6/706" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/BF9E836D20C74EF7826D8DA5345DD2F2/709" alt="img" style="zoom:50%;" />**3、3、startActivityForActivity()启动**

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/CED2CC734A70415287D6595670D56646/719" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/55FDB019F2204B05BBDC1FE19EDF3DB8/721" alt="img" style="zoom:50%;" />

​             ![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/55FDB019F2204B05BBDC1FE19EDF3DB8/721)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/B82C769BF58E4ED88F8CDCE5608E9575/723)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/BE5826CA99EA4507B86B9EB4CB6F8183/727)

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/F469C4D8BD964666BDBD679EB0BE360F/730)

两种启动方式的比较

![img](https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/2B62232A516C4E228D3F98E185B4328B/734)

### **4.Activity的停止**

**1、Activity的生命周期状态**

–运行状态：Activity存在，位于前台，可见，可以响应用户事件。

–暂停状态：Activity存在，位于前台，可见，但被遮挡，不能响应用户事件。

–停止状态：Activity存在，前台不可见，不能响应用户事件。

–销毁状态：Activity不存在。

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/4B879D9F69624AA4A306E3D0C4D2CADF/750" alt="img" style="zoom:50%;" />

**2、Activity的生命周期的回调方法**

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/0E3D213CD9FD4BCD9063F8DAFA364A4B/754" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/993FD8DC368C49FC8FBF6708953E27A8/756" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/0857AA02900749B3ABB22C223C295578/758" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/DFE39D7155D04039BACB4350DB7EB57A/760" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/5E82AF048B8D477090B5D1E5CC76F35B/762" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/8AC6B2CF0F374EA5AEC1825C1A10F69A/764" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/0A294A7C27D8479D9FFCDFB974585AB3/766" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/44D35CB1B4EB46249025C92E594D6BEA/768" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/C6F141E9703D446992D72088657DA6C6/770" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/69A882AA04574E9B96A076A0C9A69B0D/772" alt="img" style="zoom:50%;" />

### **5.Activity启动模式**

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/A9D530D4328E4CAE9EEFFD53E09F832A/775" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/54250C0FE1ED4D8A8BDF441F73217163/777" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/AF2614476DC54B1AAF405284960C4E79/780" alt="img" style="zoom:50%;" />

<img src="https://note.youdao.com/yws/public/resource/0e89c777a3d9902be4a0aa48ac731ddf/xmlnote/48640872BD4C4554B00D89B3C22E2180/783" alt="img" style="zoom:50%;" />