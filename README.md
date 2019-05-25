# CS9223 Deep Learning Project
The final project for CS9223 Deep Learning class was the [LANL Earthquake Prediction Competition](https://www.kaggle.com/c/LANL-Earthquake-Prediction) on Kaggle. In the competition, we address when an earthquake will take place. Specifically, we predict the time remaining before laboratory earthquakes occur from real-time seismic data. Submissions are evaluated using the mean absolute error between the predicted time remaining before the next lab earthquake and the act remaining time.

This repository contains kernels submitted to the competition. It includes:

* Our best submission, a stacked ensemble composed of 5 sub-models:
  * GRU
  * LSTM
  * Stacked GRU
  * GRU with FFT input
  * CRNN

* A second stacked ensemble composed of 4 sub-models:
  * GRU
  * LSTM
  * Stacked GRU
  * GP

* An attempt using an autoencoder for feature extraction and an RNN for inferences
