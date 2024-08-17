# prediction-for-characteristics-of-digestion-products
## Introduce
Original Data - Robust prediction for characteristics of digestion products in an industrial-scale biogas project via typical non-time series and time-series machine learning algorithms
## abstract
Anaerobic digestion (AD) is a well-established pathway for treating agricultural organic waste, and machine learning has emerged as a novel tool to predict its product performance. However, most of the studies focused on laboratory-scale data and nontime series models. Thus, regarding time-series data from industrial-scale biogas project, the generalization performance of models was greatly limited. In this study, typical non-time series models (GBR and RF) and time-series models (LSTM, CNNLSTM, and DA-LSTM) after hyperparameter optimization were chosen to accurately predict the characteristics of digestion products in a biogas project. It indicated that the ideal GBR model for CH4 content was obtained, and the R2 values of the test set and training set were 0.93 (RMSE = 1.11) and 0.97 (RMSE = 0.69), respectively.Temperature was the most important parameter for biogas production according to feature importance and SHAP analysis of the RF model. The DA-LSTM was superior to LSTM and CNN-LSTM for the prediction of biogas production, and the R2 of DA-LSTM was 0.87 (RMSE = 1048.14) with a seq_len of 10 d. This study provides theoretical direction for real-time control, high-efficiency biogas production, and system stability of biogas projects with the aid of reliable machine learning models.
