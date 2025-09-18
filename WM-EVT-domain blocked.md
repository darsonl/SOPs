Welmore.com.tw 被擋

Date: 2025/7/3

Author: Darson Lai

發現網路都正常只有welmore.com.tw無法連線，ping會過時，tracert發現跳不出去內網第一個就過時

登進去L7設備console看log發現

![](media/e08ddb3ef3eb3bf725620ea530a10ec354c69675.png){width="6.260415573053368in"
height="3.46875in"}

這代表是政府的惡意名單被更新到我們L7設備導致域名被擋

這時候就需要加白名單

![](media/3f5c7ebba3d7a9b68bd0b402373029f7b05cadee.png){width="6.260415573053368in"
height="3.5104166666666665in"}

![](media/3447ccd9d9dd0d279fbfce5bfe96a2604d4516a9.png){width="6.260415573053368in"
height="4.03125in"}

啟用白名單

![](media/f9d7879de1a3d27f3d0ad607e0ec35e87e0b409f.png){width="6.260415573053368in"
height="4.697916666666667in"}

最後記得上傳設定

![](media/e590030dc8681b85c95fd45c98348a88acd54c1e.png){width="6.260415573053368in"
height="3.8020833333333335in"}
