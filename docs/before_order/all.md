<!-- Output copied to clipboard! -->

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.426 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Fri Nov 10 2023 02:20:13 GMT-0800 (PST)
* Source doc: 未命名文件
----->


*格式說明：任務（角色）

一個人員/帳號可以有多種角色


#### 建立訂單（行政）



1. 收到客戶詢價或下訂通知時
2. **_[新建訂單](https://cam.remotenc.com/batchupload/)頁面_**
    1. 搜集訂單來源資訊，將詢價資訊加入訂單附檔
        1. 若是來自電子郵件，將電子郵件內容截圖加入訂單附檔
        2. 若是來自傳真，將傳真內容拍照或掃描下來後加入訂單附檔
        3. 若是有採購單，則將採購單檔案也加入訂單附檔，並記得將採購單號 key 進系統
        4. 如果訂單來源資訊含有重要內容，也可加入訂單附檔，或註明於訂單備註
    2. 上傳工程圖前置作業
        5. 調整檔名，使其符合料號（報價單的使用料號）
        6. 確認工程圖檔格式為 pdf, png, dwg, dxf, stp, x_t, igs
        7. 將目前已有的資訊輸入欄位中
    3. 訂單狀態是「建檔中」
3. **_訂單細節頁面_**
    4. 確認生成的工程圖清晰度，及是否只包含一個工件
        8. 若不夠清晰，使用 AutoCAD 調整重新生成 pdf，並使用「補圖檔」功能
        9. 若包含超過一個工件，則代表應當建立為兩個料號，使用 CAD 拆圖後，重新上傳，建立兩個料號
4. **_修改訂單頁面 或 [訂單列表](https://cam.remotenc.com/order_list/) 頁面_**
    5. 將訂單狀態調整為「等待估價」或「確認下訂」


#### 審圖估價（業務）



1. **_[訂單列表](https://cam.remotenc.com/order_list/) 頁面_**
    1. 找狀態為「等待估價」的訂單
2. **_訂單細節頁面_**
    2. 填入價格至尚無價格資料的訂購物品
    3. 選擇性填寫製程相關資料
        1. 如材料、邊界盒、表處、毛胚大小等資訊
            1. 若有材料相關資訊，可以自動生出叫料單
        2. 如外發商及進價相關資訊
3. **_修改訂單頁面 或 [訂單列表](https://cam.remotenc.com/order_list/) 頁面 或 該訂單細節頁面_**
    4. 完成後，將訂單狀態調整為「可報價」


#### 報價（行政）



1. **_[訂單列表](https://cam.remotenc.com/order_list/) 頁面_**
    1. 找尋「可報價」訂單，進入該訂單細節頁面，使用生成報價單功能
2. 將報價單 Email 給客戶
3. **_修改訂單 頁面_**
    2. 更新訂單狀態為「已報價」，並將報價單及報價 Email 的截圖加入訂單檔案中