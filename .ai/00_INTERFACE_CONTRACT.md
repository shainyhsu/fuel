# 00_INTERFACE_CONTRACT.md（Jet A Fuel Calculator：黑盒契約與選擇性讀取索引）

- 頁面：https://shainyhsu.github.io/fuel/ ；主檔 index.html（716 行），單一檔案、無建置步驟、無外部腳本。
- 索引核對：2026-11-25，main（V16）。行號會隨改版漂移，以函數名稱為準：`grep -n "function 名稱" index.html` 重新定位，再更新本索引。
- 短上下文紅線（SSSM）：不整檔貼上，一律「函數定位＋局部片段（≤150 行／6,000 字元）」。

## 函數索引（index.html）

- densLbFromTemp() L458–460
- tempFromDensLb() L461–463
- getDensLb() L466–471
- displayDens() L473–482
- wtToLb() L484
- lbToDisp() L485
- setUnit() L487–513
- updateDensityFromTemp() L515–520
- updateRemainInfo() L522–540
- showTotals() L542–568
- calcFromTop() L571–594
- onAddWt() L597–628
- onAddGal() L631–647
- onAddLiters() L650–667
- clearAll() L669–684
- sync() L713
