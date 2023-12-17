# MajorProject_Anomaly-Detection-in-Weather-Data-Using-LSTM-Autoencoder
* This project delves into the innovative application of Long Short-Term Memory (LSTM) autoencoders for anomaly detection, a critical task in various domains such as cybersecurity, industrial maintenance, and healthcare. 
* It focuses on anomalies in climate and weather related data. Anomalies in climate time series data can signify extreme events, changes in climate patterns, or data collection errors that may have far-reaching implications for environmental science and policy. Often indicative of abnormal behaviour or faults, they can have substantial repercussions if not promptly identified.
* Traditional methods have limitations in capturing complex temporal dependencies in sequential data, motivating the utilisation of LSTM autoencoders, which combine the power of LSTMs in modelling sequences with the efficiency of autoencoders in learning data representations.

Thus, here we investigate the effectiveness of this approach by training LSTM autoencoders on normal data, enabling them to learn the underlying patterns. When subjected to anomalies, deviations from learned patterns trigger reconstruction errors, serving as anomaly indicators.

LSTM model (using TensorFlow) is implemented and is focused to transform the original dataset into time-series sequences, each consisting of 128 temperature samples and 30 timesteps, achieving a minimal reconstruction error.
