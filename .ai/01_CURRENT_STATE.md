# 01_CURRENT_STATE.md（SSSM 語義狀態空間快照）

- 最後更新：2026-11-25 09:09（台灣時間）

## 1. 逐字任務目標（Verbatim Objective & Done Criteria）

- 當前唯一原子任務：MWG 修正。Shainy 2026-11-25 08:04 逐字：「開始修正，在不改變或降低安全、ui、計算、效能的前提下（可變好，不可變差）。」
- 完成驗收條件：畫面與計算結果不變（main 與分支逐字、逐像素比對）；一個分支、一個 PR，Shainy 說合併才合併。

## 2. 已驗證事實（Verified Facts）

- 版本：main 為 V15（2026-11-13 09:36）；本分支 V16。〔程式碼核對〕
- 狀態只存 localStorage 的 theme；無外部腳本、Service Worker、manifest、IndexedDB。〔程式碼核對〕

## 3. 未驗證想法與待確認假設（Unverified，不得當作已實作）

- 待 Shainy 指定。

## 4. 已套用變更與下一步唯一動作（Applied Changes & Immediate Next Action）

- 已修改檔案（2026-11-25，分支 theme-meta，PR 待合併）：index.html（開頁腳本與切換鈕同步 `<meta name="color-scheme">`）、README.md、CHANGELOG.md（V16）、AGENTS.md（改指向 .ai/）、新建 .ai/00–02。
- 下一步唯一動作：待 Shainy 指定。
