# BLHeli_PCB
电子调速器

![52d6956f878a1b07242ee1acfde1d413532a2a67](https://user-images.githubusercontent.com/23308519/154173732-00506f0b-0cb6-40c0-af47-41fc56f9dad1.png)

电调功率管是美国万代的AON6504，参数85A30V，支持BLheli协议，支持调参功能，电调宝贝详情参考链接（之前买的一家卖完下架了）：https://item.taobao.com/item.htm?spm=a230r.1.14.8.3d856ec7Rs0qNC&id=651237859926&ns=1&abbucket=17#detail

主控是C8051F330-GMR，8051内核，QFN20PIN封装，数据手册：https://atta.szlcsc.com/upload/public/pdf/source/20171230/C17270_15146280919371222125.pdf

大概看了下走线，是通过反电动势分压星形接法搭建中性点，然后采集中性点和反电动势电压用于换向，电路如下。 
作者：mymymind https://www.bilibili.com/read/cv15278658

固件可以参考这几个：https://github.com/ccstl/BLHeli_SiLabs_Keil
https://github.com/jaxxzer/open-esc-firmware

![TIM截图20220216083804](https://user-images.githubusercontent.com/23308519/154173876-f352697f-bd9e-4922-b269-6c3cfd3dbbba.jpg)

