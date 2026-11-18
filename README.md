# 臺灣貨幣像素博物館 V3.1

主題：《從清末到現代——臺灣貨幣的演變》

這是一個使用 HTML、CSS 與 JavaScript 製作的靜態互動展覽網站，可部署至 GitHub Pages。

## 免費部署步驟

1. 登入 https://github.com/ ，前往 https://github.com/new 。
2. Repository name 建議填入 `taiwan-currency-museum`；選擇 **Public**，建立 repository。
3. 進入新 repository → **Add file → Upload files**（空白 repo 可選 uploading an existing file）。
4. 將本 ZIP **解壓縮**，上傳 `index.html`、`.nojekyll`、`README.md` 到儲存庫根目錄（不要只上傳 ZIP）。點選 **Commit changes**。
5. 進入 **Settings → Pages**。在 **Build and deployment** 設定 **Source → Deploy from a branch**。選 **Branch: main**，資料夾選 **/(root)**，點 **Save**。
6. 等候 GitHub 顯示 `Your site is live at ...`，使用 **Visit site** 開啟公開網址。範例：`https://你的帳號.github.io/taiwan-currency-museum/`。

## 後續修改

修改 `index.html` 後，在同一個 repository 上傳並覆蓋同名檔案，提交 Commit changes，網站即會再次部署，**公開網址通常不變**。

## 圖片與版權

目前館藏真實照片從博物館網站外部載入，可能因網站限制無法顯示；網站會顯示像素示意圖與來源連結。正式對外使用圖片前請確認各館藏圖片授權。取得授權後可建立 `images/`，下載允許使用的圖片並調整 `index.html` 的圖片路徑，即可避免外部連結中斷。

## 注意

- GitHub Free 的 GitHub Pages 使用公開儲存庫，網頁原始碼可供其他人查看。
- 此版本沒使用資料庫、伺服器端程式或外部 JavaScript 函式庫。
- 第二關雞蛋數量為策展遊戲估算設定，並非所有歷史市場的精確售價。
