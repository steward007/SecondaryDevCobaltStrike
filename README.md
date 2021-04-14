# [雁不过衡阳的二次开发CobaltStrike](https://github.com/Yang0615777/SecondaryDevCobaltStrike)
## 先赞后看,已成习惯.如有后门,我必完蛋⭐
## 关于二次开发后的CobaltStrike</br>
默认的CobaltStrike内存在多处流量特征,在马儿与服务端建立连接时进行流量交互.此间存在多处可疑特征已被各大杀软记录在册</br>
如:卡巴斯基,诺顿,迈克菲等，但国内杀软并无此功能.</br>
此次二开为CobaltStrike4.1版本.</br>
## 效果截图
### 迈克菲截图
![9a815e8374e7f0d1f8d199f1c961bc5](https://user-images.githubusercontent.com/52184829/114645707-8f0b8f80-9d0c-11eb-9ccc-b0186286656b.png)
### 卡巴斯基截图
![8a32ef6c396fbe6625d42adb308836c](https://user-images.githubusercontent.com/52184829/114645743-9a5ebb00-9d0c-11eb-89ab-74e156407970.png)
### 诺顿截图
![c727fa6431e47dd716811da9d2597d7](https://user-images.githubusercontent.com/52184829/114645755-9f236f00-9d0c-11eb-8bba-262f6394f15f.png)
所以在客户端进行免杀的同时服务端在流量交互方面也需要特征去除,才产生了二次开发后CobaltStrike.</br>
## 注:所有的CobaltStrike上线未被查杀都基于客户端的马儿未被AV静态查杀的前提下,达到了动态免杀.
## 使用方法
### 1.将cobaltstrike.jar文件替换服务端的原有jar
![image](https://user-images.githubusercontent.com/52184829/114646079-2ec91d80-9d0d-11eb-9886-47da9869b65b.png)
### 2.将cobaltstrike.jar文件替换客户端的原有jar
![image](https://user-images.githubusercontent.com/52184829/114646148-50c2a000-9d0d-11eb-8409-8f2345bb8342.png)
### 3.请确保服务端或客户端的Java环境在Jdk10以上（包含JDK10）
## 修改特征处
### 1.修改默认DefaultProfile文件
### 2.修改checksum()函数
### 3.修改反射处dll名称
## 作者微信</br>
![mmqrcode1615447892452](https://user-images.githubusercontent.com/52184829/110867567-ef6c7300-8301-11eb-8fb9-a55274c820c9.png)
![hdImg_1b0ab579408b4131cc236bb3cdfa67de16154477928](https://user-images.githubusercontent.com/52184829/110867549-e8456500-8301-11eb-90aa-19429f07ac58.jpg) </br>
