# 租約產生器（rent-tool）

純前端的住宅租賃契約產生器，零後端、開瀏覽器即可用。結構化表單 → 產生完整合約 → 列印 PDF／匯出 Word；支援電傳／謄本（PDF 抽文字層 + 影像 OCR）與身分證辨識自動帶入，影像僅在本機辨識、不上傳。

契約範本依據：內政部 113.7.8 台內地字第 11302639334 號函修正「住宅租賃契約書」。

> 這是從個人網站工具箱拆出的獨立測試版。線上版：https://s156843217.github.io/rent-tool/

## 技術

- 純 HTML + CSS + 原生 JavaScript，無建置流程。
- 外部函式庫皆以 CDN 載入：Tesseract.js（OCR）、PDF.js（抽 PDF 文字）、Google Fonts。

## 檔案

- `index.html` — 介面、樣式、邏輯
- `rent-data.js` — 設備清單、特約範本、條款固定文字
- `style.css` — 共用設計系統樣式
