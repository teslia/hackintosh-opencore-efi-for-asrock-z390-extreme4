# hackintosh-opencore-efi-for-asrock-z390-extreme4
华擎Z390 极限玩家4 黑苹果EFI文件(OC版)    
Asrock Z390 Extreme4 OpenCore EFI files    
BIOS Version: 4.30     

## Clover Version (Clover版本)
https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4

## 已测试OSX版本 OSX Tested   
##### Catalina    
10.15.4    

## 重要说明！ Attention!
请使用**OpenCore Configurator**工具生成一个新的Mac序列号。       
Please use **OpenCore Configurator** to generate new SN.

## 已测试项目
- [x] CPU变频
- [x] 显卡硬件加速(QE/CI)（Intel UHD Graphics 630 OK）
- [x] 板载ALC1220 音频输出  （ALC1220 Soundcard OK）
- [x] DisplayPort 视频/音频输出 （DP OK）
- [x] USB 2.0 / USB 3.0
- [x] 有线网卡（Intel ETH OK）
- [x] 睡眠和唤醒
- [x] NVRAM

## 无法使用的项目 (Failed feature)
- [ ] HDMI

## 我的配置 My hardware infomation
- Intel Core i9 9900K
- Lexar SSD 480G NVM.e
- DDR4 2666 8G x4 
- VP2780 4K Display use DisplayPort

## BIOS Settings:	
1. Load UEFI Defaults	
2. Advanced	
    - CPU Intel Virtualization Technology: Enabled	 
    - VT-d: Disabled	
    - Onboard HD Audio: Enabled	
    - CSM： Disabled
    - USB Configuration, XHCI Hand-off, Enabled	
    - Super IO Configuration, Disabled	
3. Security	
Secure Boot, Disabled(by default)	
