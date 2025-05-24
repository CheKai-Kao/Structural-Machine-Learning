# StructuralMachineLearning
期末報告

### 介紹

一、任務：使用前一小時PM2.5，並給定其他輔助資料，預測未來一小時的PM2.5。

二、資料來源：中研院高解析度空氣品質擬預報資料

三、訓練資料：2020, 2021, 2022 年份，共12,771筆 (shape: 157x103)

四、測試資料：2023 年份，共4,340筆 (shape: 157x103)

五、Model: FNO (Fourier Neural Operator)、AFNO (Adaptive Fourier Neural Operator)

### FNO Paper: 
Li, Z., Kovachki, N., Azizzadenesheli, K., Liu, B., Bhattacharya, K., Stuart, A., & Anandkumar, A. (2021). Fourier Neural Operator for Parametric Partial Differential Equations. In International Conference on Learning Representations (ICLR).

### AFNO Paper:
Guibas, John and Mardani, Morteza and Li, Zongyi and Tao, Andrew and Anandkumar, Anima and Catanzaro, Bryan.(2022) “Efficient Token Mixing for Transformers via Adaptive Fourier Neural Operators”. In International Conference on Learning Representations(ICLR).

### Code

TrainFNO, TrainAFNO 為訓練程式碼

TestFNO, TestAFNO 為測試程式碼

### Reference
Kossaifi, J., Kovachki, N., Li, Z., Pitt, D., Liu-Schiaffini, M., George, R., Bonev, B., Azizzadenesheli, K., Berner, J., and Anandkumar, A. , "A Library for Learning Neural Operators", ArXiV, 2024  
https://arxiv.org/abs/2412.10354.

Kovachki, N., Li, Z., Liu, B., Azizzadenesheli, K., Bhattacharya, K., Stuart, A., and Anandkumar A. , “Neural Operator: Learning Maps Between Function Spaces”, JMLR, 2021.  https://arxiv.org/abs/2108.08481.

https://github.com/NVlabs/AFNO-transformer

### hist.png

展現展示PM2.5的濃度分布，可以呈現極度偏態。

大部分的區域濃度多接近0，但其實我們比較關注中高濃度的區域(>35)。

上圖是原始分布，下圖經過對數轉換的分布。



![30](https://github.com/user-attachments/assets/c800ece7-302f-4d92-8bb5-0831d3a703c1)
