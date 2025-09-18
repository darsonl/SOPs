信箱收寄信緩慢問題

Date: 2025/7/10

Revisions: 2025/8/19 增加匯出跟檢查匯出檔案的程序

Author: Darson Lai

先匯出信件建立.pst檔做備份

匯出後需要加回outlook為資料檔檢查是否有完整匯出

然後找outlook的 .ost檔

![一張含有 文字, 螢幕擷取畫面, 軟體, 數字 的圖片 AI
產生的內容可能不正確。](media/media/image1.png){width="5.768055555555556in"
height="4.488888888888889in"}

![一張含有 文字, 電子產品, 螢幕擷取畫面, 陳列 的圖片 AI
產生的內容可能不正確。](media/media/image2.png){width="5.768055555555556in"
height="4.418055555555555in"}

確認一下所在的槽有足夠的空間，因為會重新下載整個信箱

以下這兩個先勾起來

![一張含有 文字, 螢幕擷取畫面, 數字, 軟體 的圖片 AI
產生的內容可能不正確。](media/media/image3.png){width="3.6041666666666665in"
height="6.145833333333333in"}

通常會在 C:\\users\\user\\AppData\\Local\\Microsoft\\outlook

先關outlook，然後在ost檔後面打.bkup

重開outlook之後它會重新同步資料，這會需要點時間

同步完先用用看，如果還有問題就需要刪掉這新的.ost檔 rollback 至之前的.ost
(.bkup拿掉)

郁淳之前就是在rollback之後緩慢的問題就沒了

如果server上看到此email即將滿，可以建立一個資料檔讓使用者可以把email抓下來存在本機

不過需要注意不能直接拉folder，裡面的信會消失，如果要copy整個資料夾，需要先在本機的資料檔建立資料夾，再從server的資料檔全選再移動email到新資料夾
