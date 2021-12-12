# Dell-7460-oc

EFI来源于 [HowieHye](https://github.com/HowieHye/Dell-7460-Hackintosh-OC)，但他不更新了，我在他的基础上更新了 kexts 和 opencore并分享，再次感谢 HowieHye。

## 说明

此 EFI 适用于戴尔燃 7000 系列第二代型号为 7460 的笔记本电脑。

## 电脑配置

| 规格     | 型号                                        |
| -------- | ------------------------------------------- |
| 电脑型号 | `Dell Inspiron 7460`                        |
| 网卡     | `DW1560`                           |

## OC

- OC版本：0.7.6
- 支持安装 macOS Monterey (21A559)

## 截图

![](https://github.com/jmluang/dell-7460-oc/blob/main/images/截屏2021-12-12%20下午5.23.11.png?raw=true)
![](https://github.com/jmluang/dell-7460-oc/blob/main/images/截屏2021-12-12%20下午5.23.50.png?raw=true)

## 其他说明

- 使用前先请生成你自己的三码
- 每次升级或替换新的`EFI`后 , 最好重置一下`NVRAM`
- 如果你是 macos < 12.0 的话，用我的 EFI 可能会发生蓝牙不能用、Wi-Fi 不能用、开机慢等问题不用担心，是正常操作， [参考这里](https://github.com/acidanthera/BrcmPatchRAM/pull/12)，可以尝试启动 `BrcmBluetoothInjector.kext` 并禁用 `BlueToolFixup.kext` 

## 鸣谢

- [黑果小兵](https://github.com/daliansky/)
- [冰水加劲](https://github.com/xzhih/)
- [Xjn's Blog](https://blog.xjn819.com/)
- [Steve Zheng](https://github.com/stevezhengshiqi)
- [Sukka](https://github.com/SukkaW)
- [HowieHye](https://github.com/HowieHye/Dell-7460-Hackintosh-OC)
- [OC Auxiliary Tools-开源跨平台的OpenCore辅助工具](https://github.com/ic005k/QtOpenCoreConfig)
- 以及开发 opencore 和各种 kexts 的作者
