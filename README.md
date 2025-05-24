# StructuralMachineLearning
期末報告

一、任務：使用前一小時PM2.5，並給定其他輔助資料，預測未來一小時的PM2.5。

二、資料來源：中研院高解析度空氣品質擬預報資料

三、訓練資料：2020, 2021, 2022 年份，共12,771筆 (shape: 157x103)

四、測試資料：2023 年份，共4,340筆 (shape: 157x103)

五、MOdel: FNO (Fourier Neural Operator)、AFNO (Adaptive Fourier Neural Operator)

FNO Paper: 
Li, Z., Kovachki, N., Azizzadenesheli, K., Liu, B., Bhattacharya, K., Stuart, A., & Anandkumar, A. (2021). Fourier Neural Operator for Parametric Partial Differential Equations. In International Conference on Learning Representations (ICLR).

AFNO Paper:
Guibas, John and Mardani, Morteza and Li, Zongyi and Tao, Andrew and Anandkumar, Anima and Catanzaro, Bryan.(2022) “Efficient Token Mixing for Transformers via Adaptive Fourier Neural Operators”. In International Conference on Learning Representations(ICLR).

TrainFNO, TrainAFNO 為訓練程式碼
TestFNO, TestAFNO 為測試程式碼
資料夾「更多範例」展示多個時間點的連續24hrs的預測結果

![40](https://github.com/user-attachments/assets/921f1055-353f-4be7-a4ab-11bbe89661cc)
