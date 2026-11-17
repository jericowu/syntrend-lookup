# 三創專櫃快速查詢系統

純靜態網頁，可部署 GitHub Pages，支援手機與桌面瀏覽器。

## 部署
1. 在 GitHub 建立公開 repository（例如 `syntrend-lookup`）。
2. 將本資料夾內的 `index.html`、`style.css`、`app.js`、`data.js`、`maps/` 上傳至 repository 根目錄。
3. Repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save。
4. 網址通常為 `https://你的帳號.github.io/syntrend-lookup/`。

## 資料與限制
- `data.js`：依提供的 Excel 整理副牌／商品資料，並依樓層圖人工整理主要專櫃名稱及櫃號。
- `maps/`：13 張原始平面圖（B2、1F–12F）。
- Excel 部分內容是商品描述、分類及副牌混合排列；搜尋結果保留原文，並標示販售專櫃及來源列號。並非每個副牌都有獨立櫃號；僅在專櫃名稱可對應時顯示「參考櫃號」。
- 「已無販售」工作表未納入現售搜尋，避免誤導；資料仍需人工定期核對。
- 圖片與 Excel 資料可能包含內部資訊或著作權內容，公開發布前請確認公司允許使用；若僅供個人工作使用，建議先用本機或受控的私人託管方式。
- 編輯資料可直接修改 `data.js`，修改後重新部署即可。
