# 🌐 Cheng-Lin Tsai — Personal Site

現代科技風格的個人網站，GitHub Pages 託管。

## 🔗 Live Site

https://mela0976.github.io/cheng-lin-tsai/

## ✏️ 新增演講經歷

編輯 `data/talks.json`，加入新項目：

```json
{
  "date": "2026-03-15",
  "title": "演講主題",
  "org": "邀請單位",
  "event": "活動名稱（選填）",
  "links": [{"label": "投影片", "url": "https://..."}],
  "tags": ["genai", "workshop"]
}
```

Push 到 GitHub 後，GitHub Pages 會自動更新。

## 🛠️ 新增專案

編輯 `data/projects.json`：

```json
{
  "title": "專案名稱",
  "desc": "專案描述",
  "url": "https://...",
  "tags": ["Tag1", "Tag2"]
}
```

## 📁 結構

```
├── index.html          # 主頁面（單頁式）
├── data/
│   ├── talks.json      # 演講經歷資料
│   └── projects.json   # 專案資料
└── README.md
```
