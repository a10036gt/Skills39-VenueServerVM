# Skills39-VenueServerVM
技藝競賽電腦修護，練習用模擬大會伺服器VM，平常練習或缺少設備時可用

OS: Alpine Linux Version 3.16.2 with Apache and DHCPd

大會伺服器IP: 192.168.240.200/16

大會伺服器DHCP: 192.168.184.1-99/16，預設未啟用(輸入rc-update add dhcpd並重啟即啟用)

手動設定固定IP位址: 192.168.1xx.100

#### 1.開啟VirtualBox，選擇匯入，點選下載的OVA檔案
![](https://github.com/a10036gt/Skills39-VenueServerVM/blob/main/%E5%9C%96%E7%89%871.png?raw=true)

#### 2. 請將選項中的MAC位址原則選為包含所有網路卡MAC位址，然後點選匯入
![](https://github.com/a10036gt/Skills39-VenueServerVM/blob/main/%E5%9C%96%E7%89%872.png?raw=true)

#### 3. 請將VM網路卡設置為橋接模式，並將其橋接到主機上額外安裝的網路卡
![](https://github.com/a10036gt/Skills39-VenueServerVM/blob/main/%E5%9C%96%E7%89%873.png?raw=true)
