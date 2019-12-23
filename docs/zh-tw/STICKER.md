# 修改 Sticker

- 圖包放入 `static/sticker` 以資料夾歸類
  - 資料夾內圖片檔名必須包含數字，從 1 開始，不得中斷，例如 insowe-1.png, insowe-2.png, 依此類推
  - 同一個資料夾內，附檔名必須相同
- 修改 `static/config.js` 的 `config.chat.sticker`
  - 一個 Object 代表一個資料夾
  - folder: 'funfunfamily', // 資料夾名稱
  - icon: 'FunFunFamily-1.png', // 代表 Icon
  - prefix: 'FunFunFamily-', // 檔名前綴
  - suffix: '.png', // 檔名後綴(包含附檔名)
  - count: 40 // 圖片張數