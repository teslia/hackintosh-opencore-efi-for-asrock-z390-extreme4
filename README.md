# hackintosh-opencore-efi-for-asrock-z390-extreme4
华擎Z390 极限玩家4 黑苹果EFI文件(OC版)    
Asrock Z390 Extreme4 OpenCore EFI files    
BIOS Version: 4.30     

## Clover Version (Clover版本)
https://github.com/teslia/hackintosh-clover-efi-for-asrock-z390-extreme4

## 已测试OSX版本 Tested OSX    
##### Catalina  
10.15.7  
10.15.6  
10.15.5    
10.15.4    

## 重要说明！ Attention!
请使用**OpenCore Configurator**工具生成一个新的Mac序列号。       
Please use **OpenCore Configurator** to generate new SN.

## 已测试项目 Tested feature
- [x] CPU变频*1
- [x] 显卡硬件加速(QE/CI)（Intel UHD Graphics 630 OK）
- [x] 板载ALC1220 音频输出  （ALC1220 Soundcard OK）
- [x] DisplayPort 视频/音频输出 （DP OK）
- [x] USB 2.0 / USB 3.0
- [x] 有线网卡（Intel ETH OK）
- [x] 睡眠和唤醒
- [x] NVRAM
- [x] 随航(Sidecar)

*1: 建议使用CPUFriend中的Tools重新生成一份属于自己的配置文件。     
*1: Use CPUFriend tools to generate a your profile is recommend!     
https://github.com/acidanthera/CPUFriend/blob/master/Instructions.md     

## 我的配置1 My hardware infomation 1
- Intel Core i9 9900K
- DDR4 2666 8G x4 
- Lexar SSD 480G NVM.e
- ViewSonic VP2780 4K Display use DisplayPort

## 我的配置2 My hardware infomation 2
- Intel Core i7 9700K
- DDR4 2666 16G x2 
- Samsung SSD 970 EVO 500GB
- ViewSonic VX2780-4k-hd-3 4K Display use DisplayPort
- AOC 2778x 2K 60Hz Display use HDMI
- BCM4360 PCI-E WiFi

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
