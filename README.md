# Time_Series_Prediction
Mini project to experiment with synthetic time series data generation and prediction models, including LSTM, GRU, BiDirectional RNN and Deep RNN. 


I. I evaluate the performance of the following models and compare the Root Mean Squared Error (RMSE) on 10 years of synthetically generated time series data vs. 30 years of data. 

* Deep Recurent Neural Network (RNN)
* BiDirectional Recurrent Neural Network (BRNN)
* Long Short-Term Memory (LSTM)
* Gated Recurrent Unit (GRU)

![1_I5iwCL8zDo9OppBPsprwTw](https://github.com/user-attachments/assets/61f38847-44c8-44f8-b915-82139c130eb7)


II. Results


![Screenshot 2025-07-08 at 10 49 29 AM](https://github.com/user-attachments/assets/158b1a20-d560-424d-b247-030632cb54a5)



![Screenshot 2025-07-08 at 10 49 50 AM](https://github.com/user-attachments/assets/80b2a39f-0603-4e66-8ec7-556dcaff70f0)



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


