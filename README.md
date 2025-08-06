# Excel檔案處理系統

這是一個前端網頁工具，可用於處理 Excel 檔案，根據來源檔案的 IVR Code 與負數金額，將資料填入目標檔案的指定欄位。

## 功能說明

- 上傳來源與目標 Excel 檔案（支援 .xlsx 和 .xls）
- 從來源檔案中擷取 Q 欄為負數的 IVR Code（A 欄前 7 碼）
- 將匹配的 IVR Code 填入目標檔案的 E 欄
- 下載處理後的結果檔案

## 部署方式

1. 將本專案上傳至 GitHub Repository
2. 進入 GitHub Repository 的 Settings → Pages
3. 選擇 `main` 分支，資料夾選 `root`
4. 儲存後即可透過 GitHub Pages 網址使用此工具

## 使用方式

1. 點選「選擇來源檔案」與「選擇目標檔案」
2. 點擊「🚀 開始處理檔案」
3. 處理完成後可下載結果檔案
