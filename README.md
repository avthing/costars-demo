# Costars 線上示範

[**合作關聯圖（costars-tool）**](https://github.com/avthing/costars-tool) 的線上示範頁，用 [Wikidata](https://www.wikidata.org/)（CC0）的電影演員資料製作：007、不可能任務、漫威系列。

**線上體驗：https://avthing.github.io/costars-demo/**

- 選一個人當原點，距離代表合作次數；3D／4D 時夥伴會沿橢圓軌道繞行，垂直軸是時間
- 時間軸可播放、拖曳；放大鏡搜尋；上一部／下一部；統計面板；工具列「？」有互動導覽
- 單一 HTML 檔、完全離線運作，頁面不會對外連線

這個 repo 只放示範頁（`index.html`）。程式碼、建置方式與用自己的資料產生圖，請見 [avthing/costars-tool](https://github.com/avthing/costars-tool)。

## 授權

[GNU AGPL-3.0](LICENSE)，Copyright (C) 2026 AVthing。內含的 three.js、anime.js 為 MIT 授權；示範資料來自 Wikidata（CC0）。
