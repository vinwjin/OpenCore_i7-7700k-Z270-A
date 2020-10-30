# OpenCore 0.5+ i7 7700k+Z270-a EFI

## 更新日期：2020年10月30日 OpenCore 0.6.2版本

## 说明

本人精力有限，本篇文章旨在分享成熟OpenCore EFI，所以不会实时更新最新版，只会更新重大版本。不会对配置所涉及功能作解释，只是分享自己的EFI。帮助你更节省时间精力。对于OpenCore的功能配置教程，请阅读以下链接，我也是从中学习知识！

## 参考文章

本仓库EFI依据参考的文章
  - [OpenCore 官方文档](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf)
  - [OpenCore Vanilla Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)
  - [使用OpenCore引导黑苹果](https://blog.xjn819.com/?p=543)
  - [精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html)
  
## 相关教程（建设中）
  - [EFI百度下载](https://pan.baidu.com/s/1lDSgyD3ENxq7xg0xqHU2ig) 提取码: 6nbt
  
## 电脑配置
  
  - 主板：PRIME Z270-A
  - CPU：i7 7700K
  - 显卡：蓝宝石RX 590 超白金 OC
  
## 推荐BIOS设置

- **禁用**

  -  `Fast Boot`—— 快速启动
  -  `VT-d` —— （如果将DisableIoMapper设置为YES，则可以启用）
  -  `CSM` —— 兼容性支持模块
  -  `CFG Lock` —— CFG 锁 (MSR 0xE2 写入保护)
  
- **启用**

  -  `VT-x`
  -  `Above 4G decoding` —— 大于 4G 地址空间解码
  -  `Hyper-Threading` —— 处理器超线程处理器超线程
  -  `Execute Disable Bit` —— 执行禁止位
  -  `OS type: Windows 8.1/10 UEFI Mode` —— 操作系统类型: 其他 


## 相关链接

- Thanks for:
  - [Acidanthera](https://github.com/acidanthera) Maintaining:
    - [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg)
    - [MacInfoPkg](https://github.com/acidanthera/MacInfoPkg)
    - [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)
