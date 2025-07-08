
# 💼 Week 02：個人簡介網站｜William Portfolio

本專案為 Hex School 前端切版任務-第二週作業。
主題為「個人品牌網站」，以前端工程師 William 為主角，呈現自我介紹、專業特質、聯絡方式與作品展示區塊，具備簡約排版與基本互動樣式。


## 📸 預覽畫面

> 💡 在此補上網站連結GitHub Pages

---

## 📁 專案結構

```

week02/
├── index.html              # 主頁 HTML 結構
├── reset.css               # Reset 樣式
├── all.css                 # 全站樣式（含 utility 與各區塊）
├── img-week2/              # 圖片資源
│   ├── people.png
│   ├── sparkle.png
│   └── ...

````

## 🧑‍💻 使用技術

- HTML5 / CSS3（使用 SCSS 巢狀語法轉譯為 all.css）
- Flexbox 版面配置
- Google Fonts 字體：`Bruno Ace SC`
- 桌機版切版，尚未支援 RWD

## 📌 版面區塊

| 區塊名稱 | 說明 |
|----------|------|
| Header | 導覽列，包含個人資訊與聯絡按鈕 |
| Main Hero | 形象區，左圖右文，含自我介紹與 CTA |
| Introduction | 自我描述與代表圖片群組 |
| About Me | 四張卡片說明個人特質與技能介紹 |
| Contact Me | 聯絡我區塊＋社群 icon |
| My Projects | 圖片展示與簡述 |
| Footer | 版權資訊 |

## 🎨 樣式設計

- 使用 SCSS 巢狀結構設計樣式
- 使用 `display: flex` 建構大部分區塊排版
- 主色為黑底＋綠色點綴（#00ffa3），營造個人風格
- 連結 hover 效果：白底轉光暈邊框＋透明度

## 🚀 如何啟動專案

1. Clone 此專案：

```
git clone https://github.com/Lotte-Syu/hex-round02-week02-flex.git
````

2. 進入專案資料夾後，使用瀏覽器打開 `index.html` 即可查看頁面

## 📒 學習心得

* 熟悉 Flexbox 在實務版面中的應用
* 加強 HTML 結構與 CSS 命名邏輯
* 練習還原設計稿並維持畫面一致性
* 建立良好檔案結構與切版流程

## 🏷️ 版權資訊

本專案僅供學習用途，不作商業使用。圖像資源來自 Hex School 課程教材。
