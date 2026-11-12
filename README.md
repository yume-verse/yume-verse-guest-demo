# 私立希恩絲學院・客人端（iPhone 測試版）

網頁：https://yume-verse.github.io/yume-verse-guest-demo/

- 用電腦瀏覽器打開，左邊是 iPhone 畫面，右邊可以切「假資料／接測試後端」和機型。
- 預設是假資料（不連網路）。「接測試後端」會讀寫 Notion「App 資料（測試）」，不會碰正式資料。
- 這個頁面是從 `yume-verse/yume-verse-guest-app` 產生的（`BUILD_SINGLE=1 npx vite build` → `node tools/build-iphone-frame.mjs`），不要直接改這裡的 index.html。
- 不含任何金鑰。
