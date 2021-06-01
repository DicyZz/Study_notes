 * [USB](#usb)
 * [USB体系架构](#usb体系架构)
 * [linux-USB子系统](#linux-usb子系统)
 * [驱动程序的数据结构](#驱动程序的数据结构)
 * [枚举](#枚举)
 * [遥测卡](#遥测卡)
 * [类驱动程序](#类驱动程序)
 * [gadget驱动程序](#gadget驱动程序)
 * [调试](#调试)
 * [查看源代码](#查看源代码)

#### USB

![image-20200903140752136](https://i.loli.net/2021/06/01/Sn7BdzGyNiJELx4.png)



#### USB体系架构

![image-20200903140842062](https://i.loli.net/2021/06/01/nmOq26axcSdBi1C.png)

![image-20200903140900744](https://i.loli.net/2021/06/01/BCf86WJMKPvusz7.png)

![image-20200903140920260](https://i.loli.net/2021/06/01/CZSB2W58FKQ6mrO.png)

![image-20200903140937969](https://i.loli.net/2021/06/01/cOI7LZBCDh2dagz.png)

**总线速度**

![image-20200903141010840](https://i.loli.net/2021/06/01/XUEGQ63WrHxCcvd.png)

**主机控制器**

![image-20200903141037144](https://i.loli.net/2021/06/01/3qfAL7kS5hIr1Tl.png)

![image-20200903141058151](https://i.loli.net/2021/06/01/qURKY3hvgmWrfwZ.png)

**传输模式**

![image-20200903141129284](https://i.loli.net/2021/06/01/aSoqYDU5dfROsn7.png)

**寻址**

![image-20200903141148272](https://i.loli.net/2021/06/01/QcJSCLe7IjshvT9.png)

![image-20200903141208628](https://i.loli.net/2021/06/01/WsRMOeI7fE2uXCb.png)



#### linux-USB子系统

![image-20200903141303245](https://i.loli.net/2021/06/01/dI6ejg9QPR5OU1f.png)

![image-20200903141322473](https://i.loli.net/2021/06/01/Xeqyug68bOkMVfY.png)



#### 驱动程序的数据结构

**usb_device结构体**

![image-20200903141413911](https://i.loli.net/2021/06/01/UPTqKrkmegEydui.png)

**URB**

![image-20200903141448330](https://i.loli.net/2021/06/01/cmWDf4oye3skuVI.png)

![image-20200903141506363](https://i.loli.net/2021/06/01/GgdNMExm2pZO7YS.png)

![image-20200903141525790](https://i.loli.net/2021/06/01/F4DlKk8RT7emuhA.png)

**管道**

![image-20200903141549413](https://i.loli.net/2021/06/01/ld7gZyPiQ1RSnrf.png)

**描述符结构**

![image-20200903141618404](https://i.loli.net/2021/06/01/7cRQEZzhTxtMgN4.png)

![image-20200903141636582](https://i.loli.net/2021/06/01/Dsow4t2Gpd8CKUa.png)

![image-20200903141701254](https://i.loli.net/2021/06/01/To2NSfmK3OtFc6P.png)



#### 枚举

![image-20200903142031630](https://i.loli.net/2021/06/01/RqP8UsowxOhgnGI.png)



#### 遥测卡

![image-20200903142200229](https://i.loli.net/2021/06/01/yPdO4QEINcpCm1a.png)

**初始化和探测过程**

![image-20200903142241942](https://i.loli.net/2021/06/01/kEemIN8KAT5WHZo.png)

![image-20200903142306900](https://i.loli.net/2021/06/01/O7fKAtbZ8FaNrL9.png)

![image-20200903142325478](https://i.loli.net/2021/06/01/PKOtvVk1fC5FmzD.png)

![image-20200903142345523](https://i.loli.net/2021/06/01/fXRqWdx8pQtymiV.png)

![image-20200903142401478](https://i.loli.net/2021/06/01/twdMSzAG8eJWBmZ.png)

![image-20200903142453401](https://i.loli.net/2021/06/01/XkhYecvPq4zsrJw.png)

![image-20200903142528313](https://i.loli.net/2021/06/01/6PdTf7ck9OUFmRy.png)

**寄存器访问**

![image-20200903142608667](https://i.loli.net/2021/06/01/PyQfLZGeoOrjASn.png)

![image-20200903142628412](https://i.loli.net/2021/06/01/wGWz1FKrvmcbVJP.png)

![image-20200903142645790](https://i.loli.net/2021/06/01/g6Cl5yaeiZqKmu8.png)

![image-20200903142703217](https://i.loli.net/2021/06/01/VWfCKNDUXq1m8M7.png)

![image-20200903142727784](https://i.loli.net/2021/06/01/sIDze9mEfUY87F5.png)

![image-20200903142806428](https://i.loli.net/2021/06/01/9n3rPigqkcemDZd.png)

**数据传输**

![image-20200903142828536](https://i.loli.net/2021/06/01/caBp4rOuly6bNqo.png)

![image-20200903142842946](https://i.loli.net/2021/06/01/Q6HlCmGnAu1URqi.png)

![image-20200903142907470](https://i.loli.net/2021/06/01/9aSgyG1wYA2buKW.png)

![image-20200903142935132](https://i.loli.net/2021/06/01/h4Nv18PcnMtOgAV.png)

![image-20200903142954305](https://i.loli.net/2021/06/01/IJmf7qKXRavCWLt.png)



#### 类驱动程序

![image-20200903143026419](https://i.loli.net/2021/06/01/zjRgTuPYxG6LrO1.png)

**大容量存储设备**

![image-20200903143100915](https://i.loli.net/2021/06/01/koxPv7Thg59GcJU.png)

![image-20200903143126287](https://i.loli.net/2021/06/01/6RPGmHcvxzDoX2O.png)

![image-20200903143150541](https://i.loli.net/2021/06/01/k548HMy9FZlamps.png)

![image-20200903143221102](https://i.loli.net/2021/06/01/QpyW5Y1XNkqtOah.png)

![image-20200903143250804](https://i.loli.net/2021/06/01/y9PacZYkUFgsJbW.png)

![image-20200903143314996](https://i.loli.net/2021/06/01/bXf8Mhw6ZQPzxGi.png)

![image-20200903143338158](https://i.loli.net/2021/06/01/xaI2OJy6qK3uNUh.png)

![image-20200903143400372](https://i.loli.net/2021/06/01/CVesqnrlYJH47dK.png)

![image-20200903143418119](https://i.loli.net/2021/06/01/Tw1CqelcytHDXxO.png)

**USB-串行端口转换器**

![image-20200903143458249](https://i.loli.net/2021/06/01/Jf8RZduMqKWiePE.png)

![image-20200903143518971](https://i.loli.net/2021/06/01/pKZDuUmQPYJhLFt.png)

![image-20200903143534840](https://i.loli.net/2021/06/01/tVAr1JHRZDuYoMs.png)

![image-20200903143552776](https://i.loli.net/2021/06/01/7KjFDVnsTNkvQ8Y.png)

**人机接口设备**

![image-20200903143628062](https://i.loli.net/2021/06/01/4K3UuvcaMSXY2Hw.png)

**蓝牙**

![image-20200903143648529](https://i.loli.net/2021/06/01/m14w6itGzSuApfQ.png)



#### gadget驱动程序

![image-20200903143726654](https://i.loli.net/2021/06/01/ypI38Gkr4UDsBPi.png)

![image-20200903143742759](https://i.loli.net/2021/06/01/tNXbz5RL8JGuMkI.png)



#### 调试

![image-20200903143809511](https://i.loli.net/2021/06/01/U3EH5TpbqjDIRka.png)

![image-20200903143829278](https://i.loli.net/2021/06/01/DcgSnB2oT4xaXPH.png)



#### 查看源代码

![image-20200903143854646](https://i.loli.net/2021/06/01/f4lvYOZc6KnpJg1.png)

![image-20200903143914607](https://i.loli.net/2021/06/01/6PaEDK8YroOJTvs.png)

![image-20200903143935060](https://i.loli.net/2021/06/01/lKMqNFvwmE74zyn.png)


