# GitHub Pages 圖文教學

這份教學適合你把倉庫 `JHO-001/MAT` 發佈成 GitHub Pages 網站。

---

## 1. 準備網站內容

1. 在倉庫根目錄建立 `index.html`。
2. 如果想要把頁面放在 `docs/` 資料夾，也可以建立 `docs/index.html`。

範例：
```html
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <title>MAT GitHub Pages</title>
</head>
<body>
  <h1>我的 GitHub Pages 網站</h1>
  <p>這是 MAT 專案的首頁。</p>
</body>
</html>
```

---

## 2. 瀏覽 GitHub Pages 設定頁面

1. 開啟瀏覽器，進入：
   `https://github.com/JHO-001/MAT/settings/pages`
2. 你會看到「GitHub Pages」設定區。

---

## 3. 選擇發佈來源（Source）

1. `Branch` 選擇：`main`
2. `Folder` 選擇：
   - 放在根目錄時選 `/(root)`
   - 放在 `docs/` 時選 `docs/`
3. 按下 `Save` 或 `Save changes`

> 如果你看到「Your site is ready to be published at ...」，代表設定成功。

---

## 4. 等待部署完成

1. GitHub 會自動開始部署。
2. 約 1~5 分鐘後，你可以看到網站網址。
3. 若成功，預期網址為：
   `https://jho-001.github.io/MAT`

---

## 5. 常見問題

- 若你沒有 `index.html`，GitHub Pages 會顯示錯誤。
- 若是 `docs/` 資料夾，請確認 `docs/index.html` 存在。
- 若你使用 `main` 分支且放在根目錄，請選 `/(root)`。

---

## 6. 內容示意圖（文字版）

1. 進入 `Settings`
2. 在側邊欄點 `Pages`
3. 選 `main` 分支
4. 選 `/(root)` 或 `docs/`
5. 點 `Save`
6. 看到綠色提示後，等待網址生成

---

## 7. 若你要我協助

我可以繼續幫你：
- 建立 `index.html`
- 幫你把內容部署到 `main` 分支
- 幫你驗證 `https://jho-001.github.io/MAT` 是否已生效
