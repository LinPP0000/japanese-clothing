# 🌸 日系衣物 - 張小姐精品店

## 專案說明

本專案為日系衣物精品店的 RWD 響應式網站，並包含 Android APP（WebView 版本）。

客戶可透過 Firebase 後台自行新增、管理商品，網站與 APP 同步更新。

## 技術架構

| 項目 | 技術 |
|------|------|
| 前端網站 | HTML / CSS / JavaScript (RWD) |
| 資料庫 | Firebase Firestore |
| 部署 | GitHub Pages |
| APP | Android WebView APK |

## 功能特色

- ✅ RWD 響應式設計，支援手機/平板/電腦
- ✅ 商品自動從 Firebase 載入
- ✅ APP 與網站內容完全同步
- ✅ 客戶可自行在 Firebase Console 管理商品

## Firebase 後台操作（給客戶）

1. 前往 [Firebase Console](https://console.firebase.google.com)
2. 選擇專案 → Firestore Database
3. 點選 `products` 集合 → 新增文件
4. 填入以下欄位：

| 欄位 | 說明 | 範例 |
|------|------|------|
| `name` | 商品名稱 | 蕾絲OL套裝 |
| `price` | 價格（數字） | 1200 |
| `image` | 圖片網址 | https://... |
| `description` | 商品描述 | 日系進口限量 |
| `createdAt` | 建立時間（timestamp） | （選 timestamp 類型） |

## 網站連結

🔗 https://YOUR_USERNAME.github.io/japanese-clothing/

## 聯絡資訊

- 電話：0938-538-538
- Email：chen5438@gmail.com
- 地址：台灣台北市大安區
