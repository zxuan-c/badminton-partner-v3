# 羽球雙打賽程播放器 + 記分 (GitHub Pages 版)

## 功能
- 輸入賽程清單（每行一場，格式：`A + B vs C + D`）。
- 顯示比賽舞台，支援上一場/下一場、隨機打散、重置。
- 新增記分板（左右隊伍各有 +1/-1、重置比分、左右交換）。
- 每場分數會單獨儲存，不會因切換場次丟失。
- 本機自動儲存，重新整理或下次打開仍保留。

## 部署到 GitHub Pages
1. 建立或打開一個 GitHub repo。
2. 把這裡的檔案 (`index.html`, `manifest.webmanifest`, `icon-512.png`) 上傳到 repo 根目錄。
3. 到 Settings → Pages → Source，選擇 `main` branch 與 `/ (root)`。
4. 幾十秒後，會在該頁看到網址，例如：
   `https://你的帳號.github.io/你的repo名/`
5. 在 iPhone Safari 開啟，分享 → 加入主畫面，即可像 App 使用。

---
