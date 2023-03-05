## 电脑配置
**电脑参数：**[HP PRODESK 600G4 SFF][2]
|配置|型号|
|----|----|
|系统|macOS Monterey 12.6.3|
|CPU|Intel Core i5-8500 @ 3.0GHz 6核6线程|
|显卡|Intel UHD Graphics 630 1536 MB|
|内存|酷兽 DDR4 2666MHz 32GB|
|硬盘|镁光 3400 1TB（NVMe SSD）|
|网卡|Intel I219-LM、Intel AC 7265|
|声卡|Conexant CX20632|
|SMBIOS|Mac mini (2018)| 
|BIOS|Q07 Ver.02.02.04 08/06/2018| 
|引导|OpenCore 0.8.8| 

## 实现功能
- CPU 睿频变频正常
- 核显 UHD630 显存 1536MB
- 随眠唤醒正常
- 硬件加速 4K HEVC/H.265解码
- 定制 USB,Type-C 正常
- 声卡、麦克风正常 内建 layout-id 为 20
- 有线网卡正常
- 无线正常 (`AC7265`)
- 蓝牙正常 (`AC7265`)

## 存在问题
- macOS下，主板内置的M.2 NvMe接口不工作不能被识别，折腾了很久都没搞好，最后某宝花了20元购置Pcie转M.2扩展卡才能识别Nvme硬盘；
![主板][3]

## 截图预览

### Monterey
![macOS Monterey][11]
### Kexts驱动
![Kext][12]
### USB定制
![USB,Type-C][13]
### CPU
![CPU 变频正常][14]
### SSD
![镁光3400][15]
### 硬件加速 
![4K HEVC/H.265解码][16]
### Geekbench 5
![Geekbench5跑分][17]


  [2]: https://support.hp.com/cn-zh/product/hp-prodesk-600-g4-small-form-factor-pc/21341193/document/c06066053#AbT8
  [3]: https://yangwenqing.com/usr/uploads/2023/03/2873318083.png
  [11]: https://yangwenqing.com/usr/uploads/2023/03/910438299.png
  [12]: https://yangwenqing.com/usr/uploads/2023/03/1385903077.png
  [13]: https://yangwenqing.com/usr/uploads/2023/03/1342900964.png
  [14]: https://yangwenqing.com/usr/uploads/2023/03/2869156124.png
  [15]: https://yangwenqing.com/usr/uploads/2023/03/2385535190.png
  [16]: https://yangwenqing.com/usr/uploads/2023/03/1921319268.png
  [17]: https://yangwenqing.com/usr/uploads/2023/03/2105998594.png
