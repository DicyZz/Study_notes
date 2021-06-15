 * [中断处理](#中断处理)
 * [softirq 和 tasklet](#softirq-和-tasklet)
 * [设备模型](#设备模型)
    * [<strong>udev</strong>](#udev)
    * [<strong>sysfs、kobject和设备类</strong>](#sysfskobject和设备类)
    * [<strong>热插拔和冷插拔</strong>](#热插拔和冷插拔)
    * [<strong>微码下载</strong>](#微码下载)
    * [<strong>模块自动加载</strong>](#模块自动加载)
 * [内存屏障](#内存屏障)
 * [电源管理](#电源管理)
 * [查看源代码](#查看源代码)

#### 中断处理

![image-20200901142214946](https://i.loli.net/2021/06/03/sbgwt9fhlKTkAo2.png)

![image-20200901142239542](https://i.loli.net/2021/06/03/3xy6HmSBljNt1PF.png)

![image-20200901142259362](https://i.loli.net/2021/06/06/pbHWCJSf3sNmrkO.png)

![image-20200901145043814](https://i.loli.net/2021/06/06/jBK6Ik5SzdHqpPm.png)

![image-20200901145411289](https://i.loli.net/2021/06/06/Qs3pjrbFMDlVuAC.png)

![image-20200901145628988](https://i.loli.net/2021/06/06/Lt3xDf1sAhzkZeW.png)



#### softirq 和 tasklet

![image-20200901145853851](https://i.loli.net/2021/06/06/jcziXFVKdelYnpm.png)

![image-20200901150205648](https://i.loli.net/2021/06/06/qNlFGmbHdBxYWUQ.png)

![image-20200901150237053](https://i.loli.net/2021/06/06/1YGarxCcgIOdiWM.png)

![image-20200901150315505](/home/jian/Documents/books/Study_notes/essential_linux_device_drivers/Linux驱动/image-20200901150315505.png)

![image-20200901171641970](/home/jian/Documents/Study_notes/essential_linux_device_drivers/Linux%E9%A9%B1%E5%8A%A8/image-20200901171641970.png)

![image-20200901171551800](/home/jian/Documents/Study_notes/essential_linux_device_drivers/Linux%E9%A9%B1%E5%8A%A8/image-20200901171551800.png)



#### 设备模型

##### **udev**

![image-20200901171907056](/home/jian/Documents/books/Study_notes/essential_linux_device_drivers/Linux驱动/image-20200901171907056.png)

![image-20200901172054215](/home/jian/Documents/books/Study_notes/essential_linux_device_drivers/Linux驱动/image-20200901172054215.png)

![image-20200901172144986](https://i.loli.net/2021/06/04/B3qZVdl2va7zMrD.png)

![image-20200901172223243](https://i.loli.net/2021/06/04/49fBwGHZprVz27i.png)

![image-20200901172240245](https://i.loli.net/2021/06/04/aJhcq3TBlENPmkn.png)



##### **sysfs、kobject和设备类**

![image-20200901181938541](https://i.loli.net/2021/06/04/32qKbgsMQV8dkyl.png)

![image-20200901182003274](https://i.loli.net/2021/06/04/xbuGOsYSRpEFtjz.png)

![image-20200901182107471](https://i.loli.net/2021/06/04/cZyU5JXONKavgBn.png)

![image-20200901185206053](https://i.loli.net/2021/06/04/mkeGwJS8y35tcXI.png)

![image-20200901185506852](https://i.loli.net/2021/06/04/b1BUjvGYgpQ3ALR.png)

![image-20200901185645091](https://i.loli.net/2021/06/04/CQpa1HyhEY8FSro.png)

![image-20200901185711787](https://i.loli.net/2021/06/04/oFPsREWD6Vn1CxA.png)

![image-20200901185742163](https://i.loli.net/2021/06/04/fnvUjkzZw7E9aSM.png)

![image-20200901185850142](https://i.loli.net/2021/06/04/mHG2UC9LkNiYW4V.png)



##### **热插拔和冷插拔**

![image-20200901193201131](https://i.loli.net/2021/06/04/9s8dFah1NqCmDXL.png)

![image-20200901193516495](https://i.loli.net/2021/06/04/ZWhlYkCD5XVwenG.png)



##### **微码下载**

![image-20200901194359401](https://i.loli.net/2021/06/04/iFMsSBg4c51Wa3v.png)

![image-20200901194415117](https://i.loli.net/2021/06/04/QSJzV4FMElirOnv.png)



##### **模块自动加载**

![image-20200901194632236](https://i.loli.net/2021/06/04/MGgyx4k2aSDPstb.png)

![image-20200901194702938](https://i.loli.net/2021/06/03/57Hzxlmh4RNV9oU.png)



#### 内存屏障

![image-20200901195118775](https://i.loli.net/2021/06/03/FHrTWVhGAq6nKb7.png)

![image-20200901195143368](https://i.loli.net/2021/06/03/M67aLrSUEKvI4mN.png)



#### 电源管理

![image-20200901195254648](https://i.loli.net/2021/06/03/yfgZjY14aFd5uhR.png)



#### 查看源代码

![image-20200901195748623](https://i.loli.net/2021/06/03/n2ySRiKBaYGAJHj.png)

![image-20200901195821456](https://i.loli.net/2021/06/03/LvkYCK8w9PtHX4g.png)



