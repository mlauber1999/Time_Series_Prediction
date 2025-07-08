# Time_Series_Prediction
Mini project to experiment with synthetic time series data generation and prediction models, including LSTM, GRU, BiDirectional RNN and Deep RNN. 


I. I compare the performance of small and large versions of the following models:
* Deep Recurent Neural Network (RNN)


![rnn](https://github.com/user-attachments/assets/aa515e3e-9c5e-4d08-8cd7-536ac0f2226f)



* BiDirectional Recurrent Neural Network (BRNN)

  
![bidirectional](https://github.com/user-attachments/assets/946cc373-c04a-4b1a-ae3f-4d63e2a93f26)

* Long Short-Term Memory (LSTM)



  
![1_Mb_L_slY9rjMr8-IADHvwg](https://github.com/user-attachments/assets/b96c84ac-714b-46e6-826c-3b871a992232)

* Gated Recurrent Unit (GRU)



![1_i-yqUwAYTo2Mz-P1Ql6MbA](https://github.com/user-attachments/assets/fca6a493-7250-405c-bf09-efa68148cc7b)



II. Results



![Screenshot 2025-07-08 at 10 12 03 AM](https://github.com/user-attachments/assets/4a0e84b8-1d3e-4e1b-bb16-1b691dba8406)
![Screenshot 2025-07-08 at 10 11 52 AM](https://github.com/user-attachments/assets/e8e5189a-cc28-4cea-a094-1bbe816c6253)
![Screenshot 2025-07-08 at 10 11 37 AM](https://github.com/user-attachments/assets/9643e136-8728-4fcf-be41-df031fa45019)
![Screenshot 2025-07-08 at 10 12 50 AM](https://github.com/user-attachments/assets/b7b20c85-49a1-4e4e-a5d3-da0f81e79300)
![Screenshot 2025-07-08 at 10 11 26 AM](https://github.com/user-attachments/assets/0957cff0-4c57-4f46-9091-4c46527beed8)
![Screenshot 2025-07-08 at 10 12 39 AM](https://github.com/user-attachments/assets/ce32251a-1b74-4144-8841-d25aa634d3ae)
![Screenshot 2025-07-08 at 10 12 30 AM](https://github.com/user-attachments/assets/65a4280c-4163-403f-bec5-f7ecd2b76d0f)
![Screenshot 2025-07-08 at 10 12 15 AM](https://github.com/user-attachments/assets/d7998d96-cb17-417f-98cb-23313e102a05)


III. Key Findings
* Larger models trained on the 3x augmented dataset (30 years) consistently achieved lower RMSE scores than their smaller counterparts, indicating better predictive performance on the synthetic winter coat sales data.

* The Bidirectional RNN outperformed all other models, achieving the lowest RMSE on both small (10 years) and large (30 years) datasets. This suggests its bidirectional architecture is particularly effective at capturing temporal patterns in seasonal sales data.

* The Deep RNN exhibited the most significant improvement in RMSE when moving from the small to the large dataset. This highlights that more complex architectures benefit substantially from increased training data.

* Training time increased noticeably for all models with the larger dataset, with the largest models requiring the most time to converge. This aligns with expectations given the increased data volume and model complexity.

* Visual inspection of predicted vs. actual sales plots confirmed that larger models provided a closer fit to the data, especially in capturing seasonal peaks and troughs.

IV. Skills Demonstrated
* Time series data generation and synthetic data augmentation

* Implementation and training of RNN-based architectures (including Deep RNNs and Bidirectional RNNs)

* Comparative model evaluation using RMSE and visual analysis

* Analysis of model performance scaling with dataset size

* Interpretation of results in the context of model complexity and data availability

* Effective communication of findings through clear visualizations and reporting


