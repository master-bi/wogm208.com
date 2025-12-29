如何放圖片不跑掉

你的 index.html 在 /tw、/en 這些子資料夾裡。
如果圖片放在網站根目錄的 /img/（建議），子資料夾頁面要用 ../img/ 取圖。

✅ 這個修正版 ZIP 已把所有 index.html 的 ./img/ 轉成 ../img/

你需要確保：
- 網站根目錄存在 /img/ 資料夾
- /img/ 內有：logo.webp、banner1.webp、banner2.webp、banner3.webp、card-live.webp、card-elec.webp、card-girl.webp、game-mt-live.webp、game-mt-elec.webp、game-beauty.webp 等
