# Homework 2

**第一部分 (Image Generation)：**

1. 在此部分會請同學以 generative adverisal network (GAN) 以及 diffusion 來完成圖像生成 
2. 同學可以依照 `hw2_1_StudentID.ipynb` 來完成本部分
3. 其中 GAN 的部分可以參考此[連結](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html)
4. Diffusion 的部分由於訓練較耗時，所以本次讓同學練習Sampling的過程，我們在提供的程式內有撰寫了部分程式，請同學完成 `TODO` 部分即可
5. 評分標準將依照作業説明的配分，並基於實作的效果和正確性以及報告内容給分。
6. 請將討論以及圖片一併呈現在 `ipynb` 內
7. 本部分繳交時上傳 `hw2_1_StudentID.ipynb` 即可e.g.,  `hw2_1_123456.ipynb`

**第二部分 (Document Classification)：**

在開始這部分以前，請先執行下列步驟：

1. 請先加入 [Kaggle 比賽](https://www.kaggle.com/competitions/2023-deeplearning-hw2-news-classification)
2. 於 Kaggle 比賽的資料區，下載此次作業所需的資料。
3. 同學請於第一次上傳後將組名改為學號

此部分的評分標準如下：

1. Data Preprocessing (佔總分 10%)
2. Transformer (佔總分 40%), 其中 超越 Kaggle Baseline (15%), 問題討論 (5%), Kaggle Challenger Award (20%),
3. 此部分合計 佔總分 50%。

此部分的注意事項如下：

1. 關於 Kaggle Baseline，只需超越Public Leaderboard 的Baseline就可以得到完整的分數 (15%)，不採記名次分數。
2. 關於 Kaggle Challenger Award ，是以Private Leaderboard 為判定基準，詳細基準請參考pdf內的說明。總分數為20% ，同樣不採記名次分數。
3. 繳交的程式 請依照 `hw2_2_<student_id>.ipynb` 來命名  e.g., `hw2_2_309511000.ipynb`，助教會從頭執行您的程式，並獲得對應的 `submission.csv`。
4. 產生出來的 submission file 須與您上傳至 Kaggle 比賽的 submission file 相近。
5. 若您擔心產生的 submission file 會與 上傳的差距過大，可附上您的 model weight 於繳交的 zip 內(若檔案過大，可改附上雲端連結)，但助教一樣執行上述的指令，故請在內部寫好如何讀取 weight 等等。
6. 請將討論一併呈現在 `ipynb` 內。
7. 此部分請繳交 `hw2_2_<StudentID>.zip`，裡面須包含

- `hw2_2_<student_id>.ipynb`
- `submission.csv`
- `train.csv`
- `test.csv`

同學可參考 `expected_result_of_hw2-2.zip` 來確認此部分的繳交格式

**Bonus (Prompt-based Learning)**

1. 在加分題部分，同學可以自由選擇要不要實作
2. 同學可以依照 `bonus.ipynb` 內的提示來完成 `TODO`，同時呈現訓練資料以及測試資料的準確率及Loss，即可獲得分數
3. 若同學有實作此部分，請額外上傳 `bonus.ipynb`.
