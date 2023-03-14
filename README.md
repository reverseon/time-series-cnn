# Time-series prediction using CNN
This model tries to predict time-series data, that is, the SPY close price from January 1993 to May 2022, by using the CNN architecture.
 
Based on the sliding-window algorithm, the data are labeled `BUY`, `SELL`, and `HOLD`. If it’s at its peak in that sliding window, then it’s a `SELL`. If it’s in the troughs, then it’s a `BUY`. Otherwise, it’s a `HOLD`.

We combine many technical indicators and intervals to create a B&W image such that each pixel represents a technical indicator at a certain interval.

We use this B&W image to predict at a certain price point should it SELL, BUY, or HOLD

The complete report is available in [this link](https://github.com/reverseon/time-series-cnn/blob/main/Tugas%203_DeepLearning_Kelompok%2010.pdf) (written in Bahasa Indonesia)
