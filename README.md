# JIASIN 個人自動化公開說明網站

此目錄僅包含公開介紹、隱私權政策與使用條款，沒有 Gmail 資料、API 金鑰或 n8n 憑證。

## 頁面與維護入口

- `index.html`：工具介紹。
- `privacy.html`：資料存取、AI 第三方處理、執行紀錄保存與撤銷方式。
- `terms.html`：使用範圍與操作限制。
- `styles.css`：共用樣式。

維護者：JIASIN。更新流程用途或第三方服務時，應先同步更新政策與日期。

## 發布

GitHub 儲存庫：`pk88995/jiasin-automation`。

GitHub Pages 使用 `main` 分支根目錄。只上傳本目錄的網站檔案，不上傳上層自動化工作區。

## Google OAuth 品牌設定

- 應用程式名稱：`JIASIN 個人自動化`
- 首頁：`https://pk88995.github.io/jiasin-automation/`
- 隱私權政策：`https://pk88995.github.io/jiasin-automation/privacy.html`
- 服務條款：`https://pk88995.github.io/jiasin-automation/terms.html`
- 網站授權網域：`pk88995.github.io`，保留既有 n8n 回呼所需網域。
- 支援與開發者聯絡信箱：`ftn7303@gmail.com`

上述網址需在 GitHub Pages 部署完成、確認可公開存取後使用。

發布為正式運作與 Google 品牌 / 資料存取驗證是不同程序；此網站不保證通過 Google 驗證。若要求網站所有權，可使用 Search Console 的 HTML 驗證檔或 meta tag 驗證指定的 URL 前綴；沒有 github.io 的 DNS 控制權。

切換正式運作後，在 n8n 重新連接 Gmail account，並先以唯讀的查詢節點確認授權。此網站的建立不會啟用或執行 Gmail 自動化流程。
