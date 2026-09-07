# 楠梓美食清單 — 規格

## 資料來源
23 篇 Threads share 連結（見 urls.txt），需登入的 Chrome 讀取。

## 收錄範圍
- 主體：高雄市楠梓區
- 放寬：距「高雄市楠梓區後昌路132號」車程 15 分鐘內（約半徑 5–7 km，含左營北端、橋頭南端、仁武交界）
- 超出範圍者：保留在資料裡但預設不顯示，用行政區篩選切換

## 價格分級（單人一餐）
- $   ≤ 150
- $$  150 < x ≤ 500
- $$$ > 500

## 每家店欄位
name, aliases, category, price_tier, price_note,
address_full, district, lat, lng, gmaps_url,
hours: { mon..sun: [{open,close}] | "closed" },
meal_slots: [breakfast|lunch|dinner|latenight],
closed_days, signature_items[], note,
source_urls[], verified_date, hours_confidence: high|medium|low

## 二次查證（Q1=B）
每家店查 Google/店家粉專補地址與營業時間；卡片標「資料查證日」；
查不到時 hours_confidence=low 並顯示「請點 Google Maps 確認」。

## 網頁
手機一頁式 Artifact。篩選：種類 / 價格 / 時段 / 現在營業中 / 行政區。
卡片含一鍵開 Google Maps 導航 + 原始 Threads 連結。關鍵字搜尋。
想吃/已吃打勾（先用 localStorage，跨裝置同步之後再說）。
