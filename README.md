# Hackintosh-12490F-MSI_B660M_MORTAR_WIFI_DDR4-AMD_6650XT

## 设备配置

| 类型        | 型号                              |
|-----------|------------------------------------|
| CPU       | Intel Core i5 12490F |
| 主板        | MSI MAG B660M MORTAR WiFi DDR4 |
| 显卡        | 瀚铠 AMD RX 6650XT 合金版 8GB |
| 内存        | 金百达 银爵长鑫 32GB DDR4 3200（16GB x 2，超频至3466） |
| SSD        | 西部数据 SN750 500GB + 铠侠 RC20 1T|
| 电源        | 鑫谷 GM650w 冰山版全模组 |
| 机箱        | 铝元素 mini（前置 1 x USB3.0 Type-A + 1 x 10GB Type-C） |
| WiFi/蓝牙 | 主板自带 Intel AX211 |

## BIOS设置
1. 关闭
  - Intel VT-D
  - CFG Lock
  - CSM（选择仅UEFI)。
  - 安全启动
  - 微星的快速开机
  - 微软的快速开机

## 实测/建议环境
- macOS Ventura 13.5 (22G74)
- BIOS版本：7D42v1D 发布日期 2023-07-18，其他版本应该也可以
- macOS12 及以下版本应该能开机，但无线网卡驱动可能需要替换成12版本的

## 正常工作
- 无线网卡、蓝牙
- 有线网卡（没测试，理论正常）
- USB 速率正常（不同机箱可能需要自行定制USB）
- 显卡
- 硬件解码
- 后置和前置音频输出（仅测试了3.5mm单插口耳机）
- 其他待测试...

## 已知问题
- 显卡在日常工作中的频率较高，可能需要降频降低负载
- Airdrop 无解

## 鸣谢
- [国光的黑苹果安装教](https://apple.sqlsec.com)
- [黑果小兵的部落阁](https://blog.daliansky.net)
- 本 EFI 修改自 [corot2a的EFI](https://github.com/corot2a/Hackintosh-12700KF-B660M-MORTAR-6650XT)
