# HP ProDesk800 G1 TWR Hackintosh

这个 EFI 源自：[https://github.com/Chosimja/HP-Elitedesk-800-G1-Hackintosh](https://github.com/Chosimja/HP-Elitedesk-800-G1-Hackintosh)，通过 OCAT 将 OC 升级到了目前最新版本1.0.2，对应的 Kext 也做了自动升级。目前在自己的机器（TWR，塔式机器）上做了验证，可以正常引导 Catalina 和 Monterey 两个版本的系统。我的机器是塔式TWR，SFF和MFF 不确定是否可以直接用。

基于目前的配置，睡眠可以通过鼠标和键盘唤醒。接下来的计划：

* USB端口定制
* 增加 Intel Wi-Fi（现有的，还未启用）
* 尝试 Funsion Drive



## 黑苹果工具
* https://dortania.github.io/OpenCore-Install-Guide/
* https://github.com/dortania/OpenCore-Legacy-Patcher
* ProperTree: https://github.com/corpnewt/ProperTree
* GenSMBIOS: https://github.com/corpnewt/GenSMBIOS
* gibMacOS：https://github.com/corpnewt/gibMacOS
* Hackintool：https://github.com/headkaze/Hackintool
* USBMap：https://github.com/corpnewt/USBMap
* OCAT: https://github.com/ic005k/OCAuxiliaryTools/