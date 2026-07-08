# Giloo LA 2026 Deck

Giloo 在 Getting Real '26（洛杉磯，2026/07/22）的演講簡報。
場次：**Beyond Festivals and Streamers — How Films Find Audiences, Unlock Values, and Drive Impact**

## 這是什麼

- 簡報本體是**單一自包含 HTML**：[`public/index.html`](public/index.html)（約 42 頁投影片，字型用 Google Fonts CDN，無其他外部依賴）。
- **上線網址：** https://giloo-la-2026.netlify.app/

## 怎麼改（重點）

**直接編輯 `public/index.html`，然後 push 到 `main` 分支就會自動上線。**

每次推上 `main`，GitHub Action（`.github/workflows/deploy.yml`）會自動把 `public/`
部署到上面的 Netlify 網址，網址永遠不變，約 1 分鐘生效。

### 用手機改（不用電腦）

1. 手機瀏覽器打開 **claude.ai/code**（需 Claude Pro/Max），登入。
2. 連到這個 repo：`rurushih0422-create/giloo-la-2026-deck`。
3. 用中文講要改什麼，例如「把封面副標改成 XXX」「第 9 頁那段數字改成 90%」。
4. Claude 改完 `public/index.html` 並 push，Action 自動部署，重新整理網址就看到。

## 設計系統

深色系（Giloo Joinus dark）：底色 navy #0e0f11，品牌紅 #ea2b40 只用在 eyebrow 標籤與強調字，
字型 Geist Sans / Noto Sans TC。詳見桌面 `design.md`。
