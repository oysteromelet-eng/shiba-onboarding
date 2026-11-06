# 🐕 柴柴探險隊迎新基地

## 目前版本

V0.8-1.5 Luxury Character Card Complete

---

## 網站網址

https://oysteromelet-eng.github.io/shiba-onboarding/

---

# 專案簡介

透過柴柴探險隊迎新活動，協助學生：

- 認識自己
- 認識同學
- 建立班級歸屬感
- 完成探險闖關
- 加入班級柴柴牆

---

# 已完成功能

## ✅ V0.5 基礎角色版

- GitHub Pages 上線
- 柴柴代號產生器
- 特質徽章
- 柴柴故事
- 猜猜我是誰
- localStorage 自動儲存
- localStorage 自動恢復

---

## ✅ V0.6 探險關卡版

Step0 首頁

↓

Step1 入隊報到

↓

Step2 柴柴代號

↓

Step3 特質徽章

↓

Step4 柴柴故事

↓

Step5 猜猜我是誰

↓

Step6 完成入隊

---

## ✅ V0.7 Firebase 班級版

Step7 柴柴牆

---

# 已完成全動態化

✅ 柴柴代號

✅ 特質徽章

✅ 柴柴故事

✅ 猜猜我是誰

---

# 已完成驗證

✅ Step0 首頁

✅ Step1 入隊報到

✅ Step2 柴柴代號

✅ Step3 特質徽章

✅ Step4 柴柴故事

✅ Step5 猜猜我是誰

✅ Step6 完成入隊

✅ Step7 柴柴牆

---

# Firebase

## Firebase Project

Project Name：

shiba-adventure-team

狀態：

✅ 已建立

---

## Firestore Database

✅ 已建立

Database：

(default)

方案：

Spark 免費方案

---

## Firestore Collection

Collection Name：

shibas

✅ 已建立

---

## Firestore 測試資料

✅ 第一筆測試文件建立成功

測試資料：

codeName : 測試柴柴

subject : 數學

talent : 唱歌

interest : 畫畫

dream : 老師

---

## Firebase Web App

App Name：

shiba-onboarding-web

✅ 已建立

✅ firebaseConfig 已取得

---

## Firebase SDK

✅ Firebase SDK 已接入 index.html

✅ Firebase 初始化成功

✅ Firestore 連線成功

✅ Firebase Script 可讀取 localStorage

驗證結果：

成功讀取 codeName

---

## Firestore 寫入

✅ saveShibaToFirestore() 建立完成

✅ 完成入隊後自動寫入 Firestore

✅ 第一隻網站柴柴上傳成功

流程：

完成入隊

↓

saveShibaToFirestore()

↓

addDoc()

↓

Firestore

↓

shibas Collection

---

## Firestore 讀取

✅ loadShibaWall() 建立完成

✅ getDocs() 成功

✅ 柴柴牆讀取成功

流程：

Firestore

↓

讀取 shibas Collection

↓

動態建立柴柴牆

↓

顯示所有柴柴

---

# V0.8 功能

## ✅ V0.8-1 角色卡下載

✅ downloadCharacterCard() 建立完成

✅ 動態讀取 localStorage 資料

✅ 開啟列印模式

✅ 可另存為 PDF

內容包含：

- 柴柴代號
- 最喜歡的科目
- 專長
- 興趣
- 夢想

---

## ✅ V0.8-1.5 豪華角色卡

✅ 柴柴探險隊正式隊員證標題

✅ 柴柴代號

✅ 特質徽章

✅ 柴柴故事

✅ 猜猜我是誰

✅ 彩色版面

✅ 可列印

✅ 可另存 PDF

角色卡內容：

🐕 柴柴代號

🏅 特質徽章

📖 柴柴故事

🎭 猜猜我是誰

🎖️ 柴柴探險隊正式隊員證

---

# 目前已完成成果

✅ 本機版柴柴牆

✅ Firebase 雲端資料庫

✅ Firestore 文件寫入

✅ Firestore 文件讀取

✅ 雲端班級柴柴牆

✅ 角色卡下載

✅ 豪華角色卡

✅ PDF 列印模式

---

# 下一步

## 🎭 V0.8-2 班級版猜猜我是誰

目標：

Firestore

↓

讀取全班柴柴

↓

匿名顯示提示卡

↓

點擊揭曉身份

預計功能：

- 顯示興趣、專長、夢想
- 隱藏柴柴代號
- 點擊後顯示答案
- 作為開學破冰活動使用

---

## 👩‍🏫 V0.9 教師儀表板

目標：

Firestore

↓

自動統計

↓

全班分析

預計功能：

- 全班夢想排行榜
- 全班興趣排行榜
- 全班專長排行榜
- 柴柴數量統計
- 班級迎新資料總覽

---

# 備份檔案

✅ index-backup.html

✅ index-v05-stable.html

✅ index-v06-step2-working.html

✅ index-v06-step3-working.html

✅ index-v07-shiba-wall-milestone.html

建議新增：

✅ index-v07-firestore-complete.html

✅ index-v08-luxury-card-complete.html

---

# 最後更新

V0.8-1.5 豪華角色卡完成

已達成：

✅ Firebase Project

✅ Firestore

✅ Web App

✅ Firebase SDK

✅ 雲端寫入

✅ 雲端讀取

✅ 班級柴柴牆

✅ 角色卡下載

✅ 豪華角色卡

✅ PDF 列印模式

🏫 第一版全班共用柴柴牆完成

📄 豪華角色卡完成

🚀 下一站：

V0.8-2 班級版猜猜我是誰
