# 林尚德 Shang-Te Lin — Official Website

可直接部署到 GitHub Pages 的響應式音樂家官方網站，不需要安裝任何軟體或執行建置指令。首頁保留音樂家身分、作品與官方資料，並包含「音樂筆記 Music Notes」文章系統。

## 網站內容

1. **形象照**：已使用 `assets/images/shang-te-lin-portrait.jpg`。未來可用同名檔案直接替換，建議直式 JPG/WebP，至少 1200 × 1500 px。
2. **Official Profiles**：Facebook、Instagram、Spotify、Apple Music、YouTube、IMDb 與 Taiwan Cinema 已集中列出，並同步至結構化資料。
3. **Email**：已設定為 `sd.lin@dhmusic.cc`。
4. **統一身分**：網站標題、首頁、Meta 描述與 Schema.org 均使用「林尚德 Shang-Te Lin｜音樂製作人・詞曲創作者・電影配樂 / Music Producer · Songwriter · Film Composer」。
5. **英文 Bio／獎項**：文字與獎項名稱可依最新履歷持續更新。

## 關於獎項 Logo

目前網站採用統一設計的「獎項名稱標記」，並未擅自重製官方 Logo。金馬獎官方規章要求 Logo 使用者向執委會申請標準格式檔案，且不得裁切或修改。取得各獎項官方授權檔案後，可放入 `assets/images/`，再將資歷區的文字標記換成正式圖片。

## 部署到 GitHub Pages

1. 登入 GitHub，建立新的公開 repository，例如 `shang-te-lin`。
2. 將這個資料夾內的所有檔案上傳到 repository 根目錄；請保留 `assets` 資料夾結構與 `.nojekyll`。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 將 Source 選為 **Deploy from a branch**。
5. Branch 選擇 **main**，資料夾選 **/(root)**，按 **Save**。
6. 等候數分鐘後，網站網址通常為：`https://你的帳號.github.io/shang-te-lin/`

若 repository 名稱直接設為 `你的帳號.github.io`，網址會是 `https://你的帳號.github.io/`。

## 本機預覽

直接雙擊 `index.html` 即可預覽。若字型無法顯示，請確認裝置有網路連線；網站會自動使用系統備用字型。

## 檔案結構

```text
index.html
notes/
  index.html
  music-theory-and-pop/index.html
  norwegian-wood-misreading/index.html
  were-old-songs-better/index.html
  then-and-now-lyrics/index.html
assets/
  css/style.css
  js/main.js
  images/shang-te-lin-portrait.jpg
  images/shang-te-lin-studio.jpg
  images/golden-horse-speech.jpg
.nojekyll
README.md
```

## 新增文章

每篇文章放在 `notes/文章網址/index.html`，並同步把標題、日期、分類與摘要加入 `notes/index.html` 的文章列表。若要顯示在首頁，也要把文章卡片加入首頁的「Music Notes」區塊。文章網址與 canonical URL 應保持一致。

© Shang-Te Lin / Harvest Music
