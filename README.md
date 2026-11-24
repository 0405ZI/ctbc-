# 中信科技大學校園自導之旅

## 上傳 GitHub
先解壓縮，將裡面的 index.html、style.css、app.js、sw.js、README.md 與 assets 資料夾，一起上傳至原儲存庫最外層並覆蓋同名檔案。不要上傳 ZIP，也不要多包一層資料夾。按 Commit changes，等待 Pages 發布完成。
務必同時更新 index.html，舊版可能把程式放在 HTML 裡，只換 app.js 不會生效。Pages 沿用 main 與 /(root)。

## 圖片與錄音
第一站三德樓 assets/image1.jpeg
第二站河畔綠藝所 assets/image2.jpeg
第三站白蓮霧樹 assets/image3.jpeg
第四站生活美學館 assets/image4.jpeg
第五站陶意所 assets/image5.jpeg
第六站科技場域 assets/image6.jpeg
首頁及成果老樹插畫 assets/campus-tree-art.png
USR 圖示 assets/usr-logo.png
白蓮霧唸謠 assets/white-waxapple-rhyme.m4a

換圖時進入 assets，以 Add file → Upload files 上傳同完整檔名圖片；大小寫、副檔名與實際格式須一致。首頁老樹插畫依目前確認版本保留。

## 修改內容
app.js 開頭 stations 設定關卡名稱、任務及題目。成果標題搜尋 ctx.fillText('我的中信校園探索紀錄'。首頁與各站使用的 USR 圖片保持獨立檔案，無須轉 Base64。
成果圖固定 2264×1600，修改後須重新產生。第二站主要站名保留「河畔綠藝所」，上方小字為「看見生命的不同風景」。

## 手機使用
建議活動開始前即用 Chrome（安卓）或 Safari（iPhone）開啟，LINE 內建瀏覽器可能限制下載或分享。成果頁提供下載、分享及原圖替代操作，尚未以所有手機實機驗證。用 QR Code 開啟時仍依掃碼 App 決定使用的瀏覽器。

## 草稿與授權
開始前需勾選活動個資與影像授權條款；全文可按連結閱讀。條款依提供內容呈現。
答案、照片與勾選狀態僅暫存在學生裝置，沒有集中收件後台。學生下載成果後自行繳交。更換瀏覽器、裝置或清除資料可能失去草稿，可使用備份／匯入。
sw.js 用於退役舊離線快取，不會清除學生答案或照片。
