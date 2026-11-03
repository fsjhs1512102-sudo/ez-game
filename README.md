# 🎮 CYBER-AIM 3D: VEKC OVERDRIVE
### 極限戰場 3D：賽博獵殺者 | 網頁端 3D 電競槍法與身法訓練平台

![Version](https://img.shields.bg/badge/Version-v4.0%20Final-0284c7?style=for-the-badge)
![Three.js](https://img.shields.io/badge/Three.js-R128-black?style=for-the-badge&logo=three.js)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v3.0-06B6D4?style=for-the-badge&logo=tailwindcss)
![WebGL](https://img.shields.io/badge/WebGL-60FPS-990000?style=for-the-badge&logo=webgl)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📖 專案簡介 (Introduction)

**《CYBER-AIM 3D: VEKC OVERDRIVE》** 是一款基於 **Three.js** 與 **HTML5 / WebGL** 技術打造的一頁式 Web3D 第一人稱射擊 (FPS) 訓練平台與賽博競技遊戲。

本專案無需不安裝任何外掛或大型客戶端，打開瀏覽器即可享有 60 FPS 流暢的槍力測試與身法拉扯體驗。遊戲結合了高真實度的槍械彈道後座力、立體身法技能（飛鉤抓繩、時空減速、滑行衝刺）、動態走位 AI 機器人以及重低音 **SUNO AI** 原創主題曲，為射擊遊戲玩家與 Web3D 開發者提供極致的電競感受。

---

## 💡 開發緣由與動機 (Motivation & Origin)

### 🎯 開發動機
1. **零門檻與即時性**：傳統 FPS 訓練軟體往往需要付費下載數 GB 的檔案。我們希望提供一款「**零下載、開啟即玩、毫秒級響應**」的 Web 端訓練解決方案。
2. **三維身法與槍法結合**：現有網頁標靶遊戲多為 2D 定點點擊，缺乏現代電競遊戲（如 *VALORANT*、*CS2*、*Apex Legends*）中的立體拉槍、跳躍、滑行與走位避彈。
3. **電競數據視覺化**：整合即時爆頭率 (Headshot %)、反應速度 (Reaction Time ms) 與彈藥數據，幫助玩家以科學化數據評估手感。

### 🚀 開發緣由
探索前端 3D 繪圖技術 **Three.js** 在高幀率射擊遊戲上的極限，結合 **Web Audio API** 聲學合成與 **SUNO AI** 音樂生成，驗證一頁式網頁 (Single-File App) 在互動電競與專案簡報展示上的龐大潛力。

---

## ✨ 核心特色 (Key Features)

### 🔫 1. 槍械系統與部位 Hitbox
* **四大電競槍械**：
  * **AK-Cyber**：中遠距離高爆發，伴隨真實彈道散佈與壓槍後座力。
  * **AWP-Pro**：重型狙擊槍，支援右鍵 **2.5x 光學開鏡 (ADS Scope Overlay)**。
  * **Vector-Neon**：超高射速衝鋒槍，適合搭配滑行近距掃射。
  * **Pump-X**：散彈槍，高覆蓋面彈丸制壓。
* **分區 Hitbox 傷害判定**：
  * **頭部 (Head)**：3.0x 傷害 + 金黃色浮動數字 + 專屬叮聲 (Headshot Ding)。
  * **軀幹 (Torso)**：1.0x 基礎傷害。
  * **腿部 (Legs)**：0.7x 減傷判定。

### 🏃 2. 賽博立體身法與三大技能
* **WASD 流暢物理身法**：支援空手急停、跳板彈射與低姿態滑行 (Shift / C Slide-Hop)。
* **三大戰術技能**：
  * **`Q` 鍵 - 飛鉤抓繩 (Grapple Hook)**：三維空間瞬間拉扯與高空彈射。
  * **`E` 鍵 - 時空減速 (Bullet Time Matrix)**：觸發 70% 矩陣 Slowdown 減速，輕鬆鎖定高速目標。
  * **`Z` 鍵 - 電漿爆裂 (Plasma Railgun)**：貫穿全場敵方標靶的電漿光束。

### 🤖 3. 動態 AI 機器人 (Dynamic Moving Bots)
* **AD Strafing 戰術走位**：AI 機器人具備左右橫移、急停與前後距離拉扯。
* **動態跳躍規避 (Jump Dodging)**：部分機器人會在移動中觸發戰術跳躍，訓練垂直跟槍 (Vertical Tracking)。

### 🎵 4. SUNO AI 主題曲與 Web Audio 音效
* **SUNO AI 主題曲《VEKC OVERDRIVE》**：內嵌重低音 Electro Industrial 樂曲（128 BPM），激發戰鬥節奏感。
* **Web Audio 原生合成音**：無需額外下載音訊檔，純程式碼即時合成槍聲、爆頭聲與飛鉤聲。

### 🔑 5. 隱密系統指令與開發者主控台 (代碼 67)
* **隱密代碼系統**：按下 **`~`** 鍵或點擊選單「🔑 系統指令驗證」，輸入代碼 **`67`** 即可解鎖可獨立開關的神級開發者選單：
  * **Aimbot**：自動瞄準鎖頭
  * **ESP / Wallhack**：穿牆透視標記
  * **God Mode**：鎖血無敵
  * **Rapid Fire**：狂暴連發模式

---

## 📜 開發演進歷程 (Evolution Timeline)

```
┌─────────────────────────────────────────────────────────────┐
│                 CYBER-AIM 3D ROADMAP                        │
├─────────────┬─────────────┬─────────────┬───────────────────┤
│    v1.0     │    v2.0     │    v3.0     │    v4.0 Final     │
│  原型誕生   │  賽博身法   │  動態 AI    │  旗艦完全版       │
└──────┬──────┴──────┬──────┴──────┬──────┴─────────┬─────────┘
       │             │             │                │
       ▼             ▼             ▼                ▼
 Three.js 3D  WASD 滑行身法   AD 走位 AI      全繁體中文 UI
 鏡面舞台     Q/E/Z 三大技能  部位 Hitbox     SUNO 音樂整合
 基礎人形標靶 Web Audio 聲學  2.5x 狙擊鏡     代碼 67 控制台
```

* **v1.0 - 3D 原型誕生**：完成 Three.js 第一人稱鏡頭 (Pointer Lock) 渲染與基礎網格戰場。
* **v2.0 - 賽博身法與聲效**：導入 WASD 移動、滑行衝刺、Q/E/Z 技能系統與 Web Audio 即時音效。
* **v3.0 - 動態 AI 與電競化**：開發 AD Strafing 機器人走位、頭/軀/腿部位分區傷害與 AWP 開鏡。
* **v4.0 - 旗艦完全版 (Final)**：全繁體中文介面重構、SUNO AI 音樂專區整合、一頁式官網與「代碼 67」開發者除錯控制台。

---

## 🎮 操作說明 (Controls)

| 按鍵 | 功能說明 |
| :--- | :--- |
| **`W` `A` `S` `D`** | 角色前後左右移動身法 |
| **`Space` (空白鍵)** | 跳躍 / 踩踏跳板高空彈射 |
| **`Shift` / `C`** | 低姿態滑行衝刺 (Slide) |
| **`滑鼠左鍵`** | 射擊 / 點擊鎖定視角 |
| **`滑鼠右鍵`** | AWP-Pro 2.5x 精準開鏡 (ADS) |
| **`1` `2` `3` `4`** | 切換槍械 (AK / AWP / Vector / Shotgun) |
| **`Q`** | 賽博飛鉤抓繩 (Grapple) |
| **`E`** | 時空減速 (Bullet Time) |
| **`Z`** | 電漿軌道炮 (Plasma Beam) |
| **`~` (波浪符)** | 調出「代碼 67」開發者系統指令視窗 |

---

## 🛠️ 技術棧 (Tech Stack)

* **Core Engine**: [Three.js (r128)](https://threejs.org/) - 3D 場景渲染、光效與網格物理
* **UI & Layout**: [Tailwind CSS](https://tailwindcss.com/) - 響應式佈局與擬物玻璃質感
* **Audio Engine**: Web Audio API + [SUNO AI](https://suno.com/) - 即時音效合成與音樂專區
* **Icons & Fonts**: FontAwesome v6.5, Orbitron, Noto Sans TC

---

## 💻 快速開啟方式 (Getting Started)

本專案採單頁式獨立結構 (Single-file Single-page Application)，免去建置環境流程：

1. **複製 / 下載本專案**：
   ```bash
   git clone https://github.com/your-username/cyber-aim-3d.git
   ```
2. **開啟遊戲**：
   直接使用任何支援 WebGL 的現代瀏覽器（Chrome, Edge, Firefox, Safari）雙擊開啟 `index.html` 即可流暢遊玩！

---

## 🔒 隱私與免責聲明 (Privacy & Disclaimer)

* 本專案不收集任何使用者個人資訊或裝置數據。
* 遊戲內「代碼 67」除錯功能僅供開發者離線測試與教學演示使用。
