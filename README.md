# 台指期聰明錢雷達

這是可安裝到手機主畫面的公開網頁 App（PWA）。使用者只要打開部署網址，不需安裝 Python 或執行指令。

## 建立公開網址（GitHub Pages）

1. 在 GitHub 建立一個空白 repository，例如 `taiwan-futures-radar`。
2. 將此專案推送到該 repository 的 `work` 分支。
3. 到 GitHub repository 的 **Settings → Pages**，在 **Build and deployment** 選擇 **GitHub Actions**。
4. 等待 Actions 中的 **Deploy dashboard to GitHub Pages** 完成。
5. GitHub 會提供公開網址，格式為：
   `https://<GitHub帳號>.github.io/<repository名稱>/`

## 手機安裝

* **iPhone/iPad**：以 Safari 開啟公開網址，選「分享」→「加入主畫面」。
* **Android**：以 Chrome 開啟公開網址，選「安裝應用程式」。

## FinMind 與 Telegram

在看板底部填入自己的 FinMind Token 後即可開始追蹤。Token 只保存在該裝置瀏覽器的 localStorage，不會寫進 Git repository。請勿把 Token 寫入程式碼或公開分享給他人。

此工具僅供資料研究與模擬，並不會送出真實交易委託。
