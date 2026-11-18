# Eva's Personal Archive 網站檔案

## 檔案內容
- `index.html`：網站內容與結構
- `styles.css`：配色、排版、桌機與手機版樣式
- `script.js`：手機版導覽選單互動
- `assets/`：可放置你自己的圖片與作品素材

## 預覽方式
1. 將 ZIP 解壓縮。
2. 點開 `index.html`，即可在瀏覽器預覽。
3. 網站使用 Google Fonts 載入字體；若離線預覽，會自動使用系統替代字體。

## 上傳網站
將 `index.html`、`styles.css`、`script.js` 與 `assets` 資料夾一起上傳到網站主機的同一個目錄。若使用支援靜態網站部署的平台，通常可直接部署整個解壓縮資料夾。

## 建議先替換的內容
- Hero 右側的幾何示意主視覺：可替換成自己的插畫或照片。
- Selected Works 三張示意作品：替換成實際作品圖與專案說明。
- Game & Visual Lab：逐步加入遊戲觀察、繪圖、UI 練習或關卡分析。
- 電話目前使用 `09XX-XXX-XXX` 作為示意格式，並非真實電話，請自行替換或刪除。
- Email 已填入 `113405151@g.nccu.edu.tw`。
- 校系名稱依提供內容填入「國立臺灣政治大學廣告學系」，若要正式公開，建議確認校名的官方寫法。

## 修改作品圖片的小提示
目前作品區使用 CSS 製作的抽象示意圖，不需要額外圖片檔。若要改成自己的圖片，可在 `index.html` 將 `.work-image` 區塊改成 `<img src="assets/你的圖片檔名.jpg" alt="作品描述">`，並在 `styles.css` 加上：
```css
.work-image img { width: 100%; height: 100%; object-fit: cover; display: block; }
```
