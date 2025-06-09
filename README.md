# Structural Machine Learning
期末報告

## Introdiction
* 任務：使用前一小時PM2.5，並給定位來的輔助資料，預測未來一小時的PM2.5。
* 資料來源：中研院高解析度空氣品質擬預報資料
* 訓練資料：2020, 2021, 2022 年份，共12,771筆 (shape: 157x103)
* 測試資料：2023 年份，共4,340筆 (shape: 157x103)

## Model
* FNO (Fourier Neural Operator)
* AFNO (Adaptive Fourier Neural Operator)

## FNO Paper
Li, Z., Kovachki, N., Azizzadenesheli, K., Liu, B., Bhattacharya, K., Stuart, A., & Anandkumar, A. (2021). Fourier Neural Operator for Parametric Partial Differential Equations. In International Conference on Learning Representations (ICLR)

## AFNO Paper
Guibas, John and Mardani, Morteza and Li, Zongyi and Tao, Andrew and Anandkumar, Anima and Catanzaro, Bryan.(2022) Efficient Token Mixing for Transformers via Adaptive Fourier Neural Operators. In International Conference on Learning Representations(ICLR)

## Code
* TrainFNO, TrainAFNO 為訓練程式碼
* TestFNO, TestAFNO 為測試程式碼

## FNO Code Reference
* Kossaifi, J., Kovachki, N., Li, Z., Pitt, D., Liu-Schiaffini, M., George, R., Bonev, B., Azizzadenesheli, K., Berner, J., and Anandkumar, A. , "A Library for Learning Neural Operators", ArXiV, 2024. https://arxiv.org/abs/2412.10354.
* Kovachki, N., Li, Z., Liu, B., Azizzadenesheli, K., Bhattacharya, K., Stuart, A., and Anandkumar A. , “Neural Operator: Learning Maps Between Function Spaces”, JMLR, 2021. https://arxiv.org/abs/2108.08481.

## AFNO Code Reference
https://github.com/NVlabs/AFNO-transformer

## Dataset
民生公共物聯網

# Results
![30](https://github.com/user-attachments/assets/c800ece7-302f-4d92-8bb5-0831d3a703c1)
