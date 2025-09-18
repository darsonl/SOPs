VPN建立帳號SOP

Date: 2025/7/29

Author: Darson

**威健**

有兩個連線方式: SSL VPN還有wireguard

SSL VPN架在192.168.5.104 NAS上

wireguard架在192.168.5.205漢字輩正航server上

SSL VPN:

![一張含有 文字, 軟體, 電腦圖示, 網頁 的圖片 AI
產生的內容可能不正確。](media/media/image1.png)

![一張含有 文字, 螢幕擷取畫面, 軟體, 數字 的圖片 AI
產生的內容可能不正確。](media/media/image2.png)

Wireguard:

Server端先開啟WS4W然後configure clients

![一張含有 文字, 螢幕擷取畫面, 軟體, 網頁 的圖片 AI
產生的內容可能不正確。](media/media/image3.png)

![一張含有 文字, 螢幕擷取畫面, 數字, 字型 的圖片 AI
產生的內容可能不正確。](media/media/image4.png)

Client端:

![一張含有 文字, 螢幕擷取畫面, 陳列, 軟體 的圖片 AI
產生的內容可能不正確。](media/media/image5.png)

匯入.conf檔

**微傳**

FW有架SSL VPN&IKEv2

SSL VPN server端:

![一張含有 文字, 螢幕擷取畫面, 軟體, 網頁 的圖片 AI
產生的內容可能不正確。](media/media/image6.png)![一張含有 文字,
螢幕擷取畫面, 軟體, 數字 的圖片 AI
產生的內容可能不正確。](media/media/image7.png)

![一張含有 文字, 螢幕擷取畫面, 字型, 數字 的圖片 AI
產生的內容可能不正確。](media/media/image8.png)

IKEv2 client端:

![一張含有 文字, 螢幕擷取畫面, 字型, 行 的圖片 AI
產生的內容可能不正確。](media/media/image9.png)

下載憑證

![一張含有 文字, 螢幕擷取畫面, 數字, 字型 的圖片 AI
產生的內容可能不正確。](media/media/image10.png)

跑這個會自動幫你設定VPN(用windows內建VPN功能)
