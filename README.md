# herbal-scent-quiz
# 🍵 隨身草本調香 ｜ 尋找你的專屬氣味能量
> 結合漢方草本與心靈情境的客製化香包調配測驗網頁（Single-Page Web Application）

[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-brightgreen)](https://your-username.github.io/herbal-scent-quiz/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

一款專為日常生活舒壓、氣味喜好探索設計的心理測驗與動態配方生成工具。透過 7 道輕柔的情境選擇題，去除臨床中藥的嚴肅感，引導使用者找到適合當下心境的專屬 20g 漢方草本香包配方。

---

## ✨ 專案亮點 (Features)

* **🍵 7 項精選生活化草本庫**：以烏龍茶葉為基底，搭配艾草、薄荷、薰衣草、丁香、玫瑰花、乾燥桂花，兼具調香美感與購買便利性。
* **🎨 16 款動態文青配方矩陣**：根據使用者 A/B/C/D 題目的加權計分，精確組合出 16 種文學感命名（如《睡在烏龍茶裡的雲》、《午後的風與野玫瑰》）的專屬配方。
* **🌸 空氣感與柔和漸層 UI**：卡片背景會根據使用者的答題傾向（淺粉、淺藍、淺綠、淺紫）自動進行流暢的中心極淺馬卡龍色調切換。
* **📱 全裝置 RWD 自適應**：針對手機（Mobile Viewport）與電腦桌機完美優化，直覺、流暢且具備「上一題」狀態回溯功能。
* **🎯 獨立色彩偏好記錄**：第 7 題色彩喜好單獨記錄，不干擾心理測驗配方的科學比重。

---

## 🛠️ 技術架構 (Tech Stack)

* **HTML5**：語意化標籤結構與動畫視圖分頁。
* **CSS3**：Flexbox 排版、CSS 變數（Variables）動態切換主題色、漸層與微陰影視覺。
* **JavaScript (Vanilla ES6)**：純前端狀態管理、陣列計分邏輯、歷史記錄（History Stack）實作上一題功能與動態 DOM 渲染。

> 💡 **零外部框架依賴**：完全無須安裝 `npm` 或打包工具，開啟 `index.html` 即可直接執行與部署！

---

## 🌿 香料庫與配方規則 (Herb Library)

每款生成結果皆精確由 **5 種材料** 組成，總重固定為 **20g**：

1. **烏龍茶葉**（核心基底，定香與醇厚茶韻）
2. **艾草**（草本防護與淨化）
3. **薄荷**（透亮微涼與清爽）
4. **薰衣草**（沉靜撫平與放鬆）
5. **丁香**（辛溫暖意、辟邪避穢與醒腦）
6. **玫瑰花**（高雅花香與舒壓）
7. **乾燥桂花**（溫暖甘甜）

---

## 🚀 快速開始與部署 (Quick Start)

### 本地端執行
1. Clone 此儲存庫：
   ```bash
   git clone [https://github.com/your-username/herbal-scent-quiz.git](https://github.com/your-username/herbal-scent-quiz.git)
