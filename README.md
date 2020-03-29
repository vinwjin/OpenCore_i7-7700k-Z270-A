# OpenCore_i7-7700k-Z270-A
OpenCore EFI for Hackintosh

OpenCore 官方文档
OpenCore Vanilla Guide
使用OpenCore引导黑苹果
精解OpenCore

    本人精力有限，本篇文章旨在分享成熟OpenCore EFI，所以不会实时更新最新版，只会更新重大版本。不会对配置所涉及功能作解释，只是分享自己的EFI。帮助你更节省时间精力。对于OpenCore的功能配置教程，请阅读以上链接，我也是从中学习知识！

电脑配置
主板：PRIME Z270-A
CPU：i7 7700K
显卡：蓝宝石RX 590 超白金 OC

推荐的BIOS设置

禁用：
Fast Boot —— 快速启动
VT-d —— 如果将DisableIoMapper设置为YES，则可以启用）
CSM —— 兼容性支持模块
CFG Lock —— CFG 锁 (MSR 0xE2 写入保护)

启用：
VT-x
Above 4G decoding —— 大于 4G 地址空间解码
Hyper-Threading —— 处理器超线程处理器超线程
Execute Disable Bit —— 执行禁止位
OS type: Windows 8.1/10 UEFI Mode —— 操作系统类型: 其他  
