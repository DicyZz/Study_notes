 * [嵌入式Linux](#嵌入式linux)
    * [挑战](#挑战)
 * [元器件选择](#元器件选择)
 * [工具链](#工具链)
 * [Bootloader](#bootloader)
 * [内存布局](#内存布局)
 * [内核移植](#内核移植)
 * [嵌入式驱动程序](#嵌入式驱动程序)
    * [<strong>闪存</strong>](#闪存)
    * [<strong>UART</strong>](#uart)
    * [<strong>按钮和滚轮</strong>](#按钮和滚轮)
    * [<strong>PCMCIA/CF</strong>](#pcmciacf)
    * [<strong>SD/MMC</strong>](#sdmmc)
    * [<strong>USB</strong>](#usb)
    * [<strong>RTC</strong>](#rtc)
    * [<strong>音频</strong>](#音频)
    * [<strong>触摸屏</strong>](#触摸屏)
    * [<strong>视频</strong>](#视频)
    * [<strong>CPLD/FPGA</strong>](#cpldfpga)
    * [<strong>连接性</strong>](#连接性)
    * [<strong>专用领域电子器件</strong>](#专用领域电子器件)
    * [<strong>更多驱动程序</strong>](#更多驱动程序)
 * [根文件系统](#根文件系统)
    * [<strong>NFS挂载的根文件系统</strong>](#nfs挂载的根文件系统)
    * [<strong>紧凑型中间件</strong>](#紧凑型中间件)
 * [测试基础设施](#测试基础设施)
 * [调试](#调试)
    * [<strong>电路板返工</strong>](#电路板返工)
 * [调试器](#调试器)

#### 嵌入式Linux

##### 挑战

![image-20200903192034892](https://i.loli.net/2021/06/04/nMtFYrjPQ6Ssfio.png)

![image-20200903192100984](https://i.loli.net/2021/06/04/PRM7guzFoZStsT1.png)



#### 元器件选择

![image-20200903193802491](https://i.loli.net/2021/06/04/I6KoCHGvV2SfXW3.png)

![image-20200903193821519](https://i.loli.net/2021/06/04/ZRkmjsIgBvb64zX.png)



#### 工具链

![image-20200903194532859](https://i.loli.net/2021/06/04/KdnApJDNwEOL4XP.png)

![image-20200903194550415](https://i.loli.net/2021/06/04/rpABGxXjDlvb1aN.png)



#### Bootloader

![image-20200903194658126](https://i.loli.net/2021/06/04/KB8TkV3asfgqZGt.png)

![image-20200903194720530](https://i.loli.net/2021/06/04/D7iXoOScVzbwhxy.png)

![image-20200903194753037](https://i.loli.net/2021/06/04/8P1vwros5nW6KjU.png)

![image-20200903194823692](https://i.loli.net/2021/06/04/Sm9xGiYkU2faKrF.png)

![image-20200903194841751](https://i.loli.net/2021/06/04/wkygnU3xvLs7ec5.png)



#### 内存布局

![image-20200903194914318](https://i.loli.net/2021/06/04/75rvkNqz8HS2xpF.png)

![image-20200903194933833](https://i.loli.net/2021/06/04/3QrNL7vVJHukaDM.png)



#### 内核移植

![image-20200903195000139](https://i.loli.net/2021/06/04/GJR71ZOr3qEsyvH.png)

![image-20200903195017600](https://i.loli.net/2021/06/04/z42Za3jUqbkxlCY.png)



#### 嵌入式驱动程序

![image-20200903195149474](https://i.loli.net/2021/06/04/YGlL7O8ntwaMKv3.png)

![image-20200903195208588](https://i.loli.net/2021/06/04/hn1JOtqQDR5346U.png)

##### **闪存**

![image-20200903195235693](https://i.loli.net/2021/06/04/gomxb1HW37Ilk6p.png)

##### **UART**

![image-20200903195303602](https://i.loli.net/2021/06/04/sx2aULnP5Crb3ZK.png)

##### **按钮和滚轮**

![image-20200903195359382](https://i.loli.net/2021/06/04/Zjvi5zBSmGNfxyk.png)

##### **PCMCIA/CF**

![image-20200903195427497](https://i.loli.net/2021/06/04/1CeziX8HBcbAEUT.png)

##### **SD/MMC**

![image-20200903195456561](https://i.loli.net/2021/06/04/lUN4uvTHrtwzqZG.png)

##### **USB**

![image-20200903195529004](https://i.loli.net/2021/06/04/qhxHbgY1Fvt6KXl.png)

##### **RTC**

![image-20200903195604162](https://i.loli.net/2021/06/04/LG8cWeuaI7UnJbt.png)

##### **音频**

![image-20200903195643570](https://i.loli.net/2021/06/04/C8RkmVAfhbraUpS.png)

![image-20200903195755245](https://i.loli.net/2021/06/04/C8rliFHZoDqfnSG.png)

##### **触摸屏**

![image-20200903195837513](https://i.loli.net/2021/06/04/s5GFUhniLbwxzJV.png)

##### **视频**

![image-20200903195900366](https://i.loli.net/2021/06/04/KukLHMlVQcfib91.png)

##### **CPLD/FPGA**

![image-20200903195928115](https://i.loli.net/2021/06/04/gl9MxQmPjGTaDfX.png)

##### **连接性**

![image-20200903195955270](https://i.loli.net/2021/06/04/KGTztnQvDgMq5fr.png)

##### **专用领域电子器件**

![image-20200903200028049](https://i.loli.net/2021/06/04/BHpOcmI5KxXa2wn.png)

##### **更多驱动程序**

![image-20200903200144120](https://i.loli.net/2021/06/04/Z4FTkdvMSOL62Q8.png)



#### 根文件系统

![image-20200903200618903](https://i.loli.net/2021/06/04/Z6Qi3o4Jz8HNEqk.png)

![image-20200903200647864](https://i.loli.net/2021/06/04/x9hs6KapLrXcyPD.png)

##### **NFS挂载的根文件系统**

![image-20200903200729653](https://i.loli.net/2021/06/04/2MIXdZLGWUsxawV.png)

![image-20200903200751053](https://i.loli.net/2021/06/04/2qr4vd9fSa3Oix7.png)

##### **紧凑型中间件**

![image-20200903200820654](https://i.loli.net/2021/06/04/DgCxsdbKZ5yXYG2.png)

![image-20200903200842866](https://i.loli.net/2021/06/04/SK5JuIv4Uc6Mxb9.png)



#### 测试基础设施

![image-20200903201452658](https://i.loli.net/2021/06/04/jurHoSbl9kswCty.png)



#### 调试

##### **电路板返工**

![image-20200903202422226](https://i.loli.net/2021/06/04/zZ9jlaF4yiTLM2D.png)

![image-20200903202439140](https://i.loli.net/2021/06/04/UMlqARmjPZG3FYe.png)



#### 调试器

![image-20200903202511538](https://i.loli.net/2021/06/04/SDGOyWTcVkvAY7Z.png)