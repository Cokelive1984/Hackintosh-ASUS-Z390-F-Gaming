# 黑苹果 华硕 Z390-F Gaming

# ASUS Z390-F Gaming

## 配置清单

| **<font size=4>组件</font>** | **<font size=4>品牌型号</font>**                 | **<font size=4>参数</font>**                                 |
| :--------------------------- | :----------------------------------------------- | ------------------------------------------------------------ |
| CPU                          | Intel i5 9600KF                                  | [<font color=#FF644E >链接</font>](https://ark.intel.com/content/www/cn/zh/ark/products/190884/intel-core-i5-9600kf-processor-9m-cache-up-to-4-60-ghz.html) |
| 主板                         | ASUS ROG STRIX Z390-F GAMING                     | [<font color=#FF644E >链接</font>](https://www.asus.com.cn/Motherboards/ROG-STRIX-Z390-F-GAMING/) |
| 内存                         | 美商海盗船 复仇者 PRO DDR4 3200 16g*2 RGB        | [<font color=#FF644E >链接</font>](https://www.corsair.com/zh/zh/类别/产品/CORSAIR-iCUE/内存/Vengeance-PRO-RGB-Black/p/CMW32GX4M2Z3600C18) |
| 散热器                       | ID-COOLING ZOOMFLOW 240 ARPG                     | [<font color=#FF644E >链接</font>](http://www.idcooling.com.cn/Product/detail/id/143/name/ZOOMFLOW) |
| SSD                          | HP EX950 1TB M.2 NVMe                            | [<font color=#FF644E >链接</font>](https://detail.tmall.com/item.htm?id=602451259139&spm=a1z09.2.0.0.53f62e8dQPcUGJ&_u=3gnjohf9ed) |
|                              | Intel 760P 512GB M.2 NVMe                        | [<font color=#FF644E >链接</font>](https://www.intel.cn/content/www/cn/zh/products/memory-storage/solid-state-drives/consumer-ssds/7-series.html) |
| 显卡                         | Sapphire RX VEGA64 8G HBM2 超白金                | [<font color=#FF644E >链接</font>](https://www.sapphiretech.com/zh-cn/consumer/nitro-rx-vega64-8g-hbm2-le_c) |
| WiFi & Bluetooth             | BCM943602CS 双频 1750M  & Bluetooth 4.1  PCIe x1 | [<font color=#FF644E >链接</font>](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.3aba2e8d1orW4y&id=522725741837&_u=3gnjoh2130) |
| 显示器                       | Dell U2720QM 27in 4K IPS HDR                     | [<font color=#FF644E >链接</font>](https://www.dell.com/zh-cn/shop/戴尔ultrasharp-27系列-hdr-4k显示器-u2720qm/apd/210-avej/显示器) |
| 机箱                         | 联力 双子座幻彩黑                                | [<font color=#FF644E >链接</font>](www.lian-li.com/lancool-one/) |
| 电源                         | 美商海盗船 RX650x 80PLUS 全模组                  | [<font color=#FF644E >链接</font>](https://www.corsair.com/zh/zh/类别/产品/电源装置/高级电源装置/RMx-Series/p/CP-9020178-CN) |
| 鼠标                         | 雷蛇 狂蛇精英版《守望先锋》D.Va定制              | [<font color=#FF644E >链接</font>](http://cn.razerzone.com/overwatch-dva/razer-dva-abyssus-elite) |
| 键盘                         | 罗技 K845 Cherry青轴                             | [<font color=#FF644E >链接</font>](https://www.logitech.com.cn/zh-cn/product/k845-mechanical-illuminated) |
| 音响                         | Apple HomePad                                    | [<font color=#FF644E >链接</font>](https://www.apple.com.cn/homepod/) |
| 辅助笔电                     | Apple MBP 2020 M1                                   | [<font color=#FF644E >链接</font>](https://support.apple.com/kb/SP649?locale=zh_CN) |



- **<font size=5>SMBIOS</font>**

<img src="https://raw.githubusercontent.com/Cokelive1984/Hackintosh-ASUS-Z390-F-Gaming/master/EFI/info.png" style="zoom:50%;" />





- **<font size=4>主板BIos设置</font>**

  <font color=#FF644E >F5 </font>恢复主板BIOS默认最优设置

  ~~<font color=#FF644E >F11</font> 开启Enable AI超频  （尾缀K系列CPU才可开启）~~   

  ~~Ai Tweaker - Ai智能超频  <font color=#FF644E >XMP</font>  开启  （高出标称内存频率才开启XMP）~~

  高级 - CPU设置 - Intel（VMX） Virtualization Technology  开启

  高级 - 北桥 - VT-D  关闭

  高级 - 北桥 - 大于4G地址空间解码  开启

  高级 - PCH存储设置 - SATA模式选择 AHCI 默认开启

  高级 - 网络堆栈  关闭

  高级 - USB Configguration - XHCI Hand-off  开启

  高级 - 高级电源管理(APM） -  Erp  关闭

  启动 - 启动设置 - 快速启动 - 关闭

  启动 - CSM（兼容性支持模块）开启CSM - 启动设备控制  - 选择 仅 UEFI

  启动 - 安全启动菜单 - 操作系统类型  选择 Other  其他操作系统

  <font color=#FF644E >F10</font> 保存，开机 <font color=#FF644E >F8</font>  U盘启动;

  

 - 参考论坛：[<font color=#FF644E >Tonymacx86.com</font>](tonymacx86.com)、[<font color=#FF644E >远景论坛黑苹果板块</font>](bbs.pcbeta.com/forum.php?gid=86)、[<font color=#FF644E >黑果小兵</font>](https://blog.daliansky.net/)、[<font color=#FF644E >国光</font>](https://www.sqlsec.com/)等；


