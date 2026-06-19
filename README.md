# Nomad Life — Waitlist Landing Page

等待名單登陸頁，數位遊牧多幣別記帳 App「Nomad Life」。

## 內容

- `landing_page_nomad_life.html` — 單檔登陸頁（Tailwind CDN + Supabase waitlist）

## 技術

- **樣式**：Tailwind CSS（CDN）+ 自訂 design tokens（Dark / Kinetic Horizon）
- **字型**：Plus Jakarta Sans（標題）、Manrope（內文）
- **圖示**：Phosphor Icons
- **後端**：Supabase `waitlist` table，欄位 `email` + `source`

## 本機預覽

```bash
python3 -m http.server 8000
# 開 http://localhost:8000/landing_page_nomad_life.html
```

## 上線注意

`cdn.tailwindcss.com` 僅供開發；正式部署請改用 Tailwind CLI / PostCSS 編譯。

---

© 2026 Wutopia Co., Ltd. · Taiwan
