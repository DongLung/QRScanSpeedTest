# QR Scan Speed Test

台灣乘車碼風格的 QR Code 模擬頁面，用來測試掃碼速度、刷新頻率與手機瀏覽器顯示。

## Features

- 可調整容錯率 `L / M / Q / H`，預設 `L`
- 每筆 QR 內容至少 `300 bytes`
- 可調整每次變換 QR Code 的時間
- 使用 `QRious` 高解析度 canvas 輸出
- 支援手機瀏覽器操作
- 內容為測試用模擬資料，不對應真實乘車碼格式

## Local Preview

```bash
npm run serve
```

然後打開 `http://127.0.0.1:4173/`。

## GitHub Pages

推到 GitHub 後，GitHub Actions 會自動把這個專案部署成 GitHub Pages。
