# ICND VLAN Route
虛擬區域網路間的路由活動


Vlan - Core Switch --------------- Router --------------- Core Switch - Vlan

虛擬區域網路與其他區域網路一樣，需要依賴第三層網路設備，方能彼此溝通傳遞訊息。

* 從路由器上的子介面啟動 ISL 功能

      Router(config-subid)# encapsulation isl + < vlan# >
