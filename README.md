# 我的中信校園探索紀錄

## 更新 GitHub 網站
解壓縮後，將 index.html、style.css、app.js、sw.js、README.md 及整個 assets 資料夾，一起上傳到原本儲存庫的最外層。不要上傳 ZIP 本身，也不要多包一層資料夾。按 Commit changes，等待 Pages 發布完成。

這次務必同時覆蓋 index.html：舊版程式內嵌在 HTML，只換 app.js 不會生效。新版 index.html 已改為載入外部 app.js。

Pages 設定沿用 main 與 /(root)，Custom domain 留白。電腦可按 Ctrl+F5 重新整理；不要清除還有學生草稿的瀏覽資料。

## 修改文字
關卡名稱、任務與問題位於 app.js 開頭的 stations。成果圖標題搜尋 ctx.fillText('我的中信校園探索紀錄'。成果圖固定 2264×1600 像素，須重新產生才會套用修改。

## 圖片對照
| 用途 | 路徑 |
| --- | --- |
| 第一關 校門 | assets/image1.jpeg |
| 第二關 河畔綠藝所 | assets/image2.jpeg |
| 第三關 白蓮霧樹 | assets/image3.jpeg |
| 第四關 生活美學館 | assets/image4.jpeg |
| 第五關 陶意所 | assets/image5.jpeg |
| 第六關 科技空間 | assets/image6.jpeg |
| 首頁與成果插畫 | assets/campus-tree-art.png |

到 assets 裡用 Add file → Upload files，同完整檔名上傳替換；圖片格式、副檔名及大小寫要相同。

## 手機存圖
成果頁提供下載 PNG、儲存／分享圖片、顯示原圖及另頁開啟原圖。LINE 內建瀏覽器可能限制下載，請學生一開始就用 Chrome（安卓）或 Safari（iPhone）開啟網站，避免中途換瀏覽器找不到草稿。下載後查看下載內容或檔案 App，不一定自動進相簿。尚未以安卓實機驗證所有存圖選項。

## 學生資料
答案、照片與進度只暫存在學生裝置，無教師後台、不上傳作業；學生自行繳交成果 PNG。清除瀏覽資料或換裝置可能失去草稿，請使用草稿備份。sw.js 僅供退役舊版離線快取，不會刪除本機答案。
