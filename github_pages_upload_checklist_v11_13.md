# GitHub Pages 上傳檢查清單 v11.13

## 一、上傳前確認

1. 解壓縮 `woodworking_pwa_v11_13_fold_button_stability_release.zip`。
2. 確認 ZIP 內有：
   - `index.html`
   - `clear-cache_v11_13_fold_button_stability.html`
   - `README_v11_13_release_notes.md`
   - `github_pages_upload_checklist_v11_13.md`
   - `mobile_acceptance_checklist_v11_13.md`
3. 確認 `index.html` 開啟後首頁顯示：
   - 我の木工 PWA v11.13
   - PWA v11.13 FOLD STABLE

## 二、GitHub 手機上傳步驟

1. 手機打開 GitHub 專案頁。
2. 進入 `mokkou` 專案根目錄。
3. 點 `Add file`。
4. 選 `Upload files`。
5. 上傳 ZIP 解壓縮後的檔案。
6. `index.html` 要覆蓋原本的 `index.html`。
7. Commit 訊息建議填：
   - `Update Mokkou PWA to v11.13 fold button stability release`
8. 點 Commit。

## 三、上傳後檢查

1. 等待 GitHub Pages 更新。
2. 開啟：
   - `https://xianghaoyang6-cyber.github.io/mokkou/clear-cache_v11_13_fold_button_stability.html`
3. 點「清除 PWA 快取 / Service Worker」。
4. 回到：
   - `https://xianghaoyang6-cyber.github.io/mokkou/`
5. 確認首頁顯示 v11.13。

## 四、若仍看到舊版

1. 先重新整理正式網站。
2. 再開一次清快取頁。
3. 關閉手機瀏覽器分頁。
4. 重新打開正式網址。
5. 若仍是舊版，檢查 GitHub 根目錄的 `index.html` 是否真的被覆蓋。
