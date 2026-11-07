# 🐕 柴柴探險隊迎新基地

## 目前版本

V0.8-2 Class Guess Who Complete

---

## 網站網址

https://oysteromelet-eng.github.io/shiba-onboarding/

---

# 專案簡介

透過「柴柴探險隊」故事化與遊戲化迎新活動，協助學生：

- 認識自己
- 認識同學
- 建立班級歸屬感
- 降低開學焦慮
- 建立正向班級文化
- 完成探險任務
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

Firebase + Firestore

---

# 已完成全動態化

✅ 柴柴代號

✅ 特質徽章

✅ 柴柴故事

✅ 猜猜我是誰

✅ 柴柴牆

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

✅ 已建立

---

## Firestore Database

Database：

(default)

方案：

Spark 免費方案

✅ 已建立

---

## Firestore Collection

Collection Name：

shibas

✅ 已建立

---

## Firebase Web App

App Name：

shiba-onboarding-web

✅ 已建立

✅ firebaseConfig 已取得

---

## Firebase SDK

✅ Firebase SDK 已接入

✅ Firebase 初始化成功

✅ Firestore 連線成功

✅ 成功讀取 localStorage

---

## Firestore 寫入

✅ saveShibaToFirestore() 完成

✅ 完成入隊自動寫入 Firestore

✅ 第一隻網站柴柴建立成功

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

✅ loadShibaWall() 完成

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

✅ downloadCharacterCard() 完成

✅ 動態讀取資料

✅ 瀏覽器列印模式

✅ 可另存 PDF

內容包含：

- 柴柴代號
- 科目
- 專長
- 興趣
- 夢想

---

## ✅ V0.8-1.5 豪華角色卡

✅ 正式隊員證標題

✅ 柴柴代號

✅ 特質徽章

✅ 柴柴故事

✅ 猜猜我是誰

✅ 彩色版面

✅ PDF 列印模式

角色卡內容：

🐕 柴柴代號

🏅 特質徽章

📖 柴柴故事

🎭 猜猜我是誰

🎖️ 柴柴探險隊正式隊員證

---

## ✅ V0.8-2 班級版猜猜我是誰

✅ 使用 Firestore 讀取全班資料

✅ 顯示匿名提示卡

✅ 顯示科目線索

✅ 顯示興趣線索

✅ 顯示夢想線索

✅ 隱藏柴柴代號

✅ 點擊揭曉身份

資料來源：

Firestore

↓

shibas Collection

↓

getDocs()

↓

動態建立提示卡

用途：

- 開學迎新活動
- 班級破冰活動
- 同學互相認識

---

# 目前已完成成果

✅ 探險闖關模式

✅ Firebase 雲端資料庫

✅ Firestore 文件寫入

✅ Firestore 文件讀取

✅ 雲端班級柴柴牆

✅ 豪華角色卡

✅ PDF 列印模式

✅ 班級版猜猜我是誰

---

# 下一步

## 🏆 V0.8-2.5 猜猜我是誰排行榜

目標：

全班參與猜謎

↓

累積答對次數

↓

建立排行榜

預計功能：

✅ 個人答對數統計

✅ 個人答對率統計

✅ 猜謎排行榜

✅ 本週最佳猜謎王

✅ 班級榮譽榜

---

## 📄 V0.8-3 豪華 PDF

目標：

建立收藏版角色卡

預計功能：

✅ 正式卡片版面

✅ 柴犬插圖

✅ 彩色卡牌設計

✅ 隊員編號

✅ 隊員證邊框

✅ 特質徽章

✅ 柴柴故事

✅ 猜猜我是誰

✅ QR Code

✅ 真正 PDF 匯出

✅ 收藏版列印

---

## 👩‍🏫 V0.9 教師儀表板

目標：

利用 Firestore 分析全班資料

預計功能：

✅ 全班夢想排行榜

✅ 全班興趣排行榜

✅ 全班專長排行榜

✅ 最受歡迎科目排行

✅ 柴柴總數統計

✅ 完成率統計

✅ 班級迎新資料總覽

---

## 🚀 V1.0 正式迎新版

規劃功能：

✅ 班級柴柴牆

✅ 豪華角色卡

✅ 豪華 PDF

✅ 猜猜我是誰

✅ 猜謎排行榜

✅ 本週最佳猜謎王

✅ 教師儀表板

✅ 完整班級迎新平台

---

# 備份檔案

✅ index-backup.html

✅ index-v05-stable.html

✅ index-v06-step2-working.html

✅ index-v06-step3-working.html

✅ index-v07-shiba-wall-milestone.html

✅ index-v07-firestore-complete.html

✅ index-v08-luxury-card-complete.html

建議新增：

✅ index-v08-guess-who-complete.html

---

# 給未來 Copilot

此專案名稱：

柴柴探險隊迎新基地

目前版本：

V0.8-2 Class Guess Who Complete

目前已完成：

✅ Firebase

✅ Firestore

✅ 班級柴柴牆

✅ 豪華角色卡

✅ 班級版猜猜我是誰

下一步：

V0.8-2.5 猜猜我是誰排行榜

↓

V0.8-3 豪華 PDF

↓

V0.9 教師儀表板

請直接從 V0.8-2.5 開始接續開發。

---

# 給未來 Copilot 的開發注意事項

## 專案核心理念

這不是一般表單網站。

目標是：

透過「柴柴探險隊」的故事化與遊戲化體驗，

協助學生：

- 認識自己
- 認識同學
- 建立歸屬感
- 降低開學焦慮
- 建立友善班級文化

---

## 開發原則

所有新功能必須符合：

✅ 增加趣味性

✅ 增加班級互動

✅ 增加歸屬感

✅ 增加學生參與度

✅ 國小學生可操作

✅ 保持探險隊世界觀

避免：

❌ 過度競爭

❌ 過度複雜

❌ 公開敏感個資

❌ 失去故事感

---

## 技術原則

優先順序：

1. 不破壞既有功能

2. 保持 Firebase 相容

3. 保持 Firestore 相容

4. 優先重用既有函式

5. 每完成一版建立備份檔

---

## Firestore 注意事項

Project：

shiba-adventure-team

Collection：

shibas

目前文件格式：

{
  codeName,
  subject,
  talent,
  interest,
  dream,
  createdAt
}

新增欄位前：

必須考量舊資料相容性。

---

## 柴柴牆注意事項

Step7 使用：

loadShibaWall()

↓

Firestore

↓

shibas Collection

↓

動態建立 HTML

未來修改需保持：

✅ 舊資料正常顯示

✅ Firebase 功能正常

---

## 角色卡注意事項

downloadCharacterCard()

目前支援：

✅ 柴柴代號

✅ 特質徽章

✅ 柴柴故事

✅ 猜猜我是誰

✅ PDF列印模式

豪華 PDF 必須延續以上內容。

---

## 使用者族群

主要使用者：

國小學生

次要使用者：

班導師

設計方向：

- 易懂
- 有趣
- 有成就感
- 低學習門檻

本專案以：

「班級經營價值」

優先於

「技術展示」

---

## 最重要的一句話

任何新功能都應該讓孩子覺得：

「我很期待加入這個班級。」

