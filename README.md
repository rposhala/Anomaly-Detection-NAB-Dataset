# Anomaly-Detection-NAB-Dataset
Deep learning approaches that include building a sequence to sequence MLP and also building an Autoencoder with the help of Dense, LSTM, Conv1D layers individually to reconstruct and detect the anomalies in the benchmark dataset.

About Dataset:
NAB (Numenta Anomaly Benchmark) is a novel benchmark for evaluating algorithms for anomaly detection in streaming, real-time applications. It is composed of over 50 data files designed to provide data for research in streaming anomaly detection. It is comprised of both real-world and artificial timeseries data containing labeled anomalous periods of behavior.
Link for NAB datasets GitHub Repo: https://github.com/numenta/NAB/tree/master/data

For this project, realAdExchange dataset (real-world data) from NAB was used. This dataset is Online Advertisement clicking rates, where the metrics are cost-per-click (CPC). One of the files is normal without anomalies and the other was with anomalies.

Anomalies detected, data Reconstructed are compared to original non-anomalous dataset and results are provided. 

It had been observed that Autoencoder built with Convolutional 1D layers with Mean Squared Error as an error metric to define threshod and RMSprop as the optimizer had detected anomalies and reconstructed the data exceptionally well.
