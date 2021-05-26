   * [I2C协议](#i2c协议)
         * [I2C/SMBus](#i2csmbus)
         * [I2C核心](#i2c核心)
         * [总线事物](#总线事物)
         * [EEPROC](#eeproc)
         * [实时时钟](#实时时钟)
         * [I2C-dev](#i2c-dev)
         * [使用LM-Sensors监控硬件](#使用lm-sensors监控硬件)
         * [SPI总线](#spi总线)
         * [1-Wire总线](#1-wire总线)
         * [调试](#调试)
         * [查看源代码](#查看源代码)

<!--ts-->
<!--te-->

## I2C协议

![image-20200903110119032](https://i.loli.net/2021/05/24/JD1VjTWGpaveZ3P.png)



#### I2C/SMBus

![image-20200903110217928](https://i.loli.net/2021/05/24/JCimGIT7qkXbo5D.png)

![image-20200903110239018](https://i.loli.net/2021/05/24/Yx4ghodXIypiHZG.png)



#### I2C核心

![image-20200903110639965](https://i.loli.net/2021/05/24/YcRZbkpPNyB1Erx.png)

![image-20200903111326875](https://i.loli.net/2021/05/24/qpkijESD3mo27ws.png)



#### 总线事物

![image-20200903111428901](https://i.loli.net/2021/05/24/AJf53RQkcTpLF6X.png)



#### EEPROC

![image-20200903111635465](https://i.loli.net/2021/05/24/aROzU3J6bnQIcFZ.png)

![image-20200903111648534](https://i.loli.net/2021/05/24/iBuK2CrFDgmhnNy.png)

**初始化**

![image-20200903111728871](https://i.loli.net/2021/05/24/2phX9SxlkIt3HEY.png)

![image-20200903111756797](https://i.loli.net/2021/05/24/r6stXkuClGDRpxE.png)

![image-20200903111824720](https://i.loli.net/2021/05/24/ZlJyDcjuLXT9VPn.png)

![image-20200903111845263](https://i.loli.net/2021/05/24/iewgzYEkuNALnHI.png)

![image-20200903111907162](https://i.loli.net/2021/05/24/n5b73HKC8uecOlB.png)

**探测设备**

![image-20200903111938373](https://i.loli.net/2021/05/24/NY7gSU4MsPT6Dbc.png)

![image-20200903111953300](https://i.loli.net/2021/05/24/5uLI3JzYkOPFrU1.png)

![image-20200903112010044](https://i.loli.net/2021/05/24/dGqTgXFx5YSkKp7.png)

![image-20200903112028143](https://i.loli.net/2021/05/24/uLnUExZIqHzOXMR.png)

![image-20200903112045939](https://i.loli.net/2021/05/24/HBRYAyoOe2t5m8l.png)

**检查适配器的功能**

![image-20200903112116948](https://i.loli.net/2021/05/24/F3ldIoakPqUKRtT.png)

**访问设备**

![image-20200903112146688](https://i.loli.net/2021/05/24/vp1cFz3GoANq8nx.png)

![image-20200903112207495](https://i.loli.net/2021/05/24/TnzhrLy5COBRwjb.png)

![image-20200903112233118](https://i.loli.net/2021/05/24/zuhTd5JiyGkEtas.png)

**其他函数**

![image-20200903112307480](https://i.loli.net/2021/05/24/8opXMFPVhfeUm1N.png)

![image-20200903112329382](https://i.loli.net/2021/05/24/tZ7oPzQEaHDmgLV.png)



#### 实时时钟

![image-20200903112408160](https://i.loli.net/2021/05/24/Vk1NED3thT4FORM.png)

![image-20200903112429948](https://i.loli.net/2021/05/24/X4KVMPcHWh6g2Cd.png)

![image-20200903112451235](https://i.loli.net/2021/05/24/MqnKSjTGzgOvcWE.png)

![image-20200903112512792](https://i.loli.net/2021/05/24/u4Zv27heNAnixY5.png)

![image-20200903112537093](https://i.loli.net/2021/05/24/DTEpcSXulgkIOxs.png)



#### I2C-dev

![image-20200903112638451](https://i.loli.net/2021/05/24/1fM4vjq2LxDPTsE.png)



#### 使用LM-Sensors监控硬件

![image-20200903112733723](https://i.loli.net/2021/05/24/u78CIawgynBf4sK.png)



#### SPI总线

![image-20200903112800716](https://i.loli.net/2021/05/24/jJlnTMOyBULQ4hb.png)

![image-20200903112827883](https://i.loli.net/2021/05/24/eSZ6kl478mzriJ5.png)

![image-20200903112854286](https://i.loli.net/2021/05/24/zywYMRLr1IcnkuF.png)

![image-20200903112912891](https://i.loli.net/2021/05/24/62cZCtXP4NkIdun.png)



#### 1-Wire总线

![image-20200903112944462](https://i.loli.net/2021/05/24/IWguFD46ALxir2S.png)



#### 调试

![image-20200903113006413](https://i.loli.net/2021/05/24/Ymbsn7WeLkd8iQC.png)



#### 查看源代码

![image-20200903113037626](https://i.loli.net/2021/05/24/xHIcF2Swn5yXzKe.png)

![image-20200903113053841](https://i.loli.net/2021/05/24/u5Qj9SIFHflRphG.png)

![image-20200903113110258](https://i.loli.net/2021/05/24/HwNn69m2WuOfArV.png)

![image-20200903113126765](https://i.loli.net/2021/05/24/uRsrN5XfZ6SlJcx.png)