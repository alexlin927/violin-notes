# 林震煌的製琴筆記 — GitHub Pages 網頁版

包含第 1～20 課圖文、照片放大功能、4 段影片，以及第一把琴完成紀念照。
網頁可直接使用，不需要安裝程式或執行建置。

## 上傳步驟

1. 解壓縮 violin-notes-github.zip。
2. 在 GitHub 建立一個公開（Public）儲存庫，例如 violin-notes。
3. 選 Add file → Upload files，把解壓縮後的內容全部上傳。
   index.html、style.css、app.js、assets 資料夾須在儲存庫最上層。
   請不要只上傳 ZIP，也不要把整個外層資料夾包在儲存庫裡。
4. 按 Commit changes 儲存。
5. 進入 Settings → Pages。
6. Source 選 Deploy from a branch，Branch 選 main，Folder 選 / (root)，按 Save。
7. 等 GitHub 部署完成，回到 Pages 頁面點 Visit site。

## 檔案位置

- index.html：所有網頁內容。
- style.css：外觀與手機排版。
- app.js：照片點選放大功能。
- assets/：照片、影片封面及 MP4 影片，請保留資料夾名稱和相對位置。
- .nojekyll：GitHub Pages 靜態網站設定檔。

影片採 H.264 / AAC 的 MP4 格式，播放器需由訪客點選播放，不會自動播放。
所有照片、影片皆已包含，網站不需要登入 ChatGPT。
兩個 YouTube 參考連結需連上網路才能觀看。

## 日後更新

編輯 index.html 的文字，或替換 assets 裡對應的圖片後，重新上傳同名檔案即可。
上傳後請等 GitHub Pages 部署完成；若仍顯示舊內容，重新整理網頁。
