## Deep Learning-Based Forecasting Model Using LSTM for COVID-19 Case Predictions in Malaysia

**Objective:**
This project aims to utilize a deep learning model to forecast daily COVID-19 case numbers in Malaysia, assisting policymakers in deciding when to impose or ease travel restrictions. The project involves developing an Long short-term memory (LSTM) neural network model to predict new cases based on the previous 30 days of reported case data.

**Dataset:**
Trained about 1744 official data provided by Ministry of Health Malaysia in an official GitHub page to forecast Covid-19 cases.

**Deep learning model**

The deep learning model utilized in this project is composed of three main layers: an input layer, an LSTM (Long Short-Term Memory) layer, and an output layer. 

![model_architecture](https://github.com/user-attachments/assets/74091a2c-2a61-46ba-b382-07f4104ebba6)


**Result:**

**Predictive Analysis of COVID-19 Case Trends in Malaysia:**

![prediction training](https://github.com/user-attachments/assets/1de6ca1f-bb63-4768-8cea-219f5549ed7a)

**Model Evaluation and Performance Scoring:**
![evaluation](https://github.com/user-attachments/assets/b6a06286-499d-4675-8efa-c7d6b71b7338)

**Training Loss:**
![training_loss](https://github.com/user-attachments/assets/aa36c630-3352-4e4b-a22f-74f08e81860c)

**Summary**

1) The model recorded a Mean Absolute Error (MAE) of 0.03% and a Mean absolute percentage error (MAPE) of 0.04%, well below the 1% threshold, indicating high prediction accuracy.
2) The architecture of the model consists solely of LSTM, Dense, and Dropout layers, which were carefully chosen for their effectiveness in handling sequential time-series data.
3) The LSTM layers contained 32 and 64 nodes, with the tanh activation function applied to improve the model's ability to learn and understand patterns over time.
4) The training loss, which was recorded at 0.011 which suggests that the model is effectively learning and making accurate predictions as it progresses through the training process."

**Reference:** 
Ministry of Health Malaysia. COVID-19 Public Dataset: Official Data on the COVID-19 Epidemic in Malaysia. Powered by CPRC, CPRC Hospital System, MKAK, and MySejahtera. Available at MoH.Malaysia/covid19-public.

Link: https://github.com/MoH-Malaysia/covid19-public
