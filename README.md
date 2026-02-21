# Bat-CoV-Receptor-Analysis  
A bioinformatics project analyzing coronavirus' RBD  
Python 的蝙蝠冠狀病毒受體結合域（RBD）序列相似度分析
---
研究發現，Merbecovirus可依據其受體結合域（RBD）分為四個演化支系（Clades）。其中受體的使用具有高度的演化支專一性（例如 Clade 2 對應的受體是 ACE2 ）。
利用資訊工程技術，將生物學的受體偏好假說轉化為可計算的演算法，本次將使用論文：  
Catanzaro, N. J., Wu, Z., Fan, C., Jefferson, V., Abdelgadir, A., Schäfer, A., Yount, B. L., Bjorkman, P. J., Baric, R., & Letko, M. (2025). ACE2 from Pipistrellus abramus bats is a receptor for HKU5 coronaviruses. Nature Communications, 16, 4932. https://doi.org/10.1038/s41467-025-60286-3  
其內 Table 1 所提供的 35 種病毒，分析他們的 RBD 序列並繪製出親緣關係，最後與論文內的親緣關係圖比較。

進度：
- [x] 一：自動化資料收集 ( NCBI 連線與序列解析)
- [x] 二：將下載的序列永久儲存為 `.GenBank` 檔案
- [x] 三：辨識並分離出 S 蛋白區域
- [ ] 四：實作序列切片，取得 RBD 區域
- [ ] 五：計算相似度與繪製親緣關係圖
