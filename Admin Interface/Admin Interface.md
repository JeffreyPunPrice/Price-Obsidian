
| Tabs       |                                                 | Comment                                     |
| ---------- | ----------------------------------------------- | ------------------------------------------- |
| 資料管理       |                                                 |                                             |
|            | 商戶                                              | form type                                   |
|            | 商戶小貼士                                           |                                             |
|            | 商戶報價限制                                          | *deprecated*                                |
|            | 商戶專區banner管理                                    | just manage banner in MI login page         |
|            | 商戶報價封鎖                                          |                                             |
|            | 商戶報價白名單                                         | ?                                           |
|            | 商戶監察列表                                          | query type                                  |
|            | 轉介記錄                                            | 安心訂購記錄                                      |
|            | 維修補償名單                                          | PriceCare 記錄                                |
| 內容及介面      |                                                 |                                             |
|            | [Menu管理](Menu管理)                                |                                             |
|            | [Page管理](Page管理.md)                             |                                             |
|            | 新聞稿                                             | Manage post in new_list.php                 |
|            | 新聞稿頁尾內容                                         | Manage post in new_list.php                 |
|            | eNews                                           | Manage email posts                          |
|            | [Feature Banner](Feature%20Banner.md)           |                                             |
|            | Feature Icon                                    | Apps icon portals                           |
|            | App 橫向Banner                                    |                                             |
|            | Web Icon Banner                                 | dk where it appear                          |
|            | Editor Choice                                   | dk where it appear                          |
|            | Widget                                          | dk where it appear                          |
|            | Advertorial                                     |                                             |
|            | 嵌入Youtube影片                                     | insert youtube videos in 情報                 |
|            | 網站公告                                            | 登入後在top bar看到                               |
|            | 電郵優惠內容                                          |                                             |
|            | 地標                                              | just store locations                        |
|            | 登入記錄                                            | query type                                  |
| Price會員管理  |                                                 |                                             |
|            | [Price會員](Price會員.md)                           |                                             |
| E-commerce |                                                 |                                             |
|            | [Collection管理](Collection管理.md)                 |                                             |
|            | [Campaign管理](Campaign管理.md)                     |                                             |
|            | EC首頁banner管理                                    | *deprecated*                                |
|            | EC首頁列表管理                                        | *deprecated*                                |
|            | E-commerce列表                                    | deprecated?                                 |
|            | E-commerce目錄                                    | deprecated?                                 |
|            | E-commerce Recommend產品                          | deprecated?                                 |
|            | [E-commerce推廣活動](Coupon.md)                     |                                             |
|            | E-commerce活動緩存                                  | ?                                           |
|            | 會員優惠碼                                           | ?                                           |
|            | 會員優惠簡介頁                                         | ?                                           |
|            | [EC / Price Shop 訂單記錄](訂單記錄.md)                 |                                             |
|            | WeChat限時購報告                                     | query type                                  |
|            | EC Sponsorship                                  | excels only                                 |
|            | [EC Widget](EC%20Widget.md)                     |                                             |
|            | EC Widget 設置                                    | set the EC Widget in diff categories page   |
|            | Discuss EC Widget                               |                                             |
|            | EC TNC 設置                                       | TNC = Terms and condition                   |
|            | EC產品預設內容                                        | EC footer preset                            |
|            | EC eNews                                        | email news templates                        |
|            | 拒收EC名單                                          | EC news opt out ?                           |
|            | EC退款申請                                          |                                             |
| Price Shop |                                                 |                                             |
|            | [Price Shop 商戶管理](Price%20Shop%20商戶管理.md)       |                                             |
|            | [Price Shop 產品管理](Price%20Shop%20產品管理.md)       |                                             |
|            | 批核Price Shop商戶訂閱                                | Approve price shop registration             |
|            | Price Shop 收費管理                                 | Edit service charge                         |
|            | Price Shop 優惠代碼推廣                               | Manage coupon code                          |
|            | 批核Price Shop退款                                  | Manage refund                               |
|            | Price Shop financial report                     | Download a excel file about customer trades |
|            | PriceShop交易及調整分錄報告                              | query type                                  |
|            | 網購電子結單                                          | estatements                                 |
| 推送通知       |                                                 |                                             |
|            | [Push Notification管理](Push%20Notification管理.md) |                                             |
|            |                                                 |                                             |


| 操作                  |
| ------------------- |
| [把產品放上EC](#把產品放上EC) |
**※** Database沒有sync，不同Worker更新內容會replace


### 把產品放上EC
1. Price Shop > Price Shop 產品管理
2. 搜尋產品 > 編輯產品
3. 「顯示於EC限時購」 => 是
 ![[ECRadioButton.png]]
4. 定義顯示及開售時間 
![[ECDateTime.png]]
5. 定義交易流程 (按「全部」)
![[transactionFlow.png]]
6. (optional) 定義會員價及服務收費（會員）
![[memberPrice.png]]   ![[serviceCharge.png]]
7. 按「更新」套用
![[updateButton.png]]
※ 限時搶購開始後商家無法更改產品「庫存」以外資料