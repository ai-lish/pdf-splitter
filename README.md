# 📄 PDF 工具箱

純前端 PDF 工具箱，無需上傳，所有處理都在瀏覽器內完成。

🔗 **線上使用**：https://ai-lish.github.io/pdf-splitter/

## ✨ 特色

- 🔒 **100% 私隱** — 檔案完全喺瀏覽器處理，唔上傳任何 server
- ⚡ **三種分割模式**
  - **每 N 頁一份**：例如每 3 頁切一份
  - **自訂範圍**：`1-3, 5, 7-9` → 每段一份
  - **只保留指定頁**：`1, 3, 5-7` → 合併一份
- 📦 **ZIP 打包下載** — 多份 PDF 自動 zip
- 🖨️ **解除列印限制** — 建立新的可列印副本；需要密碼時只使用你輸入的密碼
- 🎯 **拖拽操作** — Drag & drop 載入
- 📱 **響應式** — 桌面、平板、手機都可用
- 🌐 **零依賴** — 純 HTML + JS（CDN: pdf-lib + JSZip + PDF.js）

## 🚀 使用方法

1. 開 [https://ai-lish.github.io/pdf-splitter/](https://ai-lish.github.io/pdf-splitter/)
2. 拖拽 PDF 落去
3. 揀工具及設定選項
4. 撳「開始處理」
5. 按需要下載結果；分割模式會自動打包成 ZIP

「解除列印」會把未加密的 PDF 直接重新輸出，保留文字及向量內容。加密的 PDF
需要你輸入正確密碼，工具會在瀏覽器內逐頁建立可列印副本；這種副本以頁面影像
保存，所以文字選取及連結可能不會保留。

## 🛠 技術

- [pdf-lib](https://github.com/Hopding/pdf-lib) — PDF 處理
- [JSZip](https://github.com/Stuk/jszip) — ZIP 打包
- GitHub Pages 託管

## 📝 License

MIT
