
使用RS232 console 線接comsole port
putty 連線頻率 115200
登入帳號密碼:admin/admin
想請問L7 要如何正常關機?

我們是下重開指令，等待大概5秒可以斷電
 <img width="744" height="233" alt="image" src="https://github.com/user-attachments/assets/72f6442a-2af0-40f2-b1e7-061010f86273" />


復電後要如何確認服務是否正常?

接電後會自行開機
putty連設備，查看sys version 確認decryption engine 跟 gparser engine 開啟，開機不會馬上起來，要等這兩項服務起來。
 <img width="775" height="381" alt="image" src="https://github.com/user-attachments/assets/41ae318a-48ea-48a9-87f3-3e9f39af6757" />


