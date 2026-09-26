# HKChat Legal

香港生活法律教育互動示範：首頁及六個手機版應用。

- 法律你識幾多？
- 細字睇真啲
- 呢個 Post 出唔出？
- 醒目防騙
- 街坊和事佬
- 今日我做議員

內容為靜態示範，對話及回應使用預設內容，毋須後端服務。

## 發佈

`site/` 包含完整網站。推送至 `main` 後，GitHub Actions 將此目錄發佈至 GitHub Pages，毋須安裝套件或執行建置。

網站：https://chenqianwan.github.io/hkchat-legal/

## 本機預覽

```sh
python3 -m http.server 8765 --directory site
```

瀏覽 http://localhost:8765/。
