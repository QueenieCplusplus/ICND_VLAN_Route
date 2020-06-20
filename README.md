# ICND VLAN Route
虛擬區域網路間的路由活動


    Vlan - Core Switch --------------- Router on a stick--------------- Core Switch - Vlan

虛擬區域網路與其他區域網路一樣，需要依賴第三層網路設備，方能彼此溝通傳遞訊息。

* 路由器上子介面


                                   --- 0/0.1
           Router ）--------fa 0/0 --- 0/0/2
                                   --- 0/0.3


* 從路由器上的子介面啟動 ISL 功能

      Router(config-subif)# encapsulation isl + < vlan# >
