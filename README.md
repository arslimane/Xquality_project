# Xquality_project(SOH lithium battery prediction)
In this study, we have developed two models for predicting the SOH values of batteries. 
The first model called the E-LSTM model, combines an encoder and LSTM architecture, while the second model is a CNN-LSTM model. 
Both models were trained and tested using the MIT battery dataset. We observed that both models yielded improved results compared to previous works; however, the CNN-LSTM model outperformed the E-LSTM model.
Additionally, apart from predicting the SOH values of individual cells, we have devised a method based on derivatives and correlation coefficients. 
This method effectively identifies events that contribute to a decline in SOH values. By visualizing these events through plots and providing a chronological representation, we can gain insights into the factors causing the decline.

To further enhance our research, we are considering the utilization of real-world data instead of relying solely on online datasets. 
Furthermore, we aim to develop an additional model capable of predicting the current, voltage, and temperature of a given battery cell. 
By integrating both predictive models, we can forecast the future behavior of a battery and, consequently, extend its overall lifespan.
