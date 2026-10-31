# ANN & CNN Tryout

- **Case 1 (ANN):** classify `Abnormal` vs `Normal` from tabular features (`data/case1/DATA1.csv`).
- **Case 2 (CNN):** classify brain MRI images as tumor `yes` / `no` (`data/case2/DATA2/`).

## Structure
```
data/            datasets
impl/            ANN_CNN_Tryout.ipynb (both cases)
result/case<x>/  plots
result/case<x>/model/  best model (.keras)
```

## Run
Requires `tensorflow`, `scikit-learn`, `pandas`, `matplotlib`, `seaborn`. Open `impl/ANN_CNN_Tryout.ipynb` and run all cells (about 5 min on CPU). Each case ends with an inference example that uses the saved model.

## Note
Many Case 2 `valid`/`test` images are near-duplicates of `train` images, so Case 2 scores are optimistic.
