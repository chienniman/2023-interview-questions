## deadlock
* mutual exclusion 無法共用
* circular waiting
* hold and wait 等待持有
* no preemption 無法剝奪
 
## solution
* reboot
* kill pid

## prevent
* 想同順序訪問，數據訪問
* 隔離改為可讀提交
* 索引
* 拆分交易大小
* 避免同表多併發
* 設置超時參數