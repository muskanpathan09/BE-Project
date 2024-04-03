*REMAINING USEFUL LIFE(RUL) PREDICTIONS OF
AIRCRAFTS ENGINES ON CMAPSS DATASET*

Predicting the Remaining Useful Life (RUL) of aviation engines is crucial for optimizing maintenance schedules, reducing total maintenance costs, and enhancing operating safety. Traditional approaches often struggle to accurately predict RUL due to their inability to capture the complex nonlinear correlations present in engine sensor data.

In this repository, we propose a novel method that leverages a random forest regressor in combination with an ensemble of deep learning models to address these challenges. Our approach integrates various deep learning architectures, including Bidirectional Long Short-Term Memory (Bi-LSTM), Bidirectional Gated Recurrent Unit (BiGRU), Bidirectional Traditional Recurrent Neural Network (Bi-TRNN), Progressive Neural Network (ProgNet), and Deep Convolutional Neural Network (DCNN). By utilizing this diverse ensemble of models, we extract comprehensive and subtle information from the sensor input, surpassing the limitations of single-model techniques.

Our ensemble technique demonstrates robustness across different operating conditions and failure modes by synthesizing predictions from multiple deep learning models into a projected RUL domain using the random forest regressor. We validate our methodology using NASA’s C-MAPSS datasets and showcase its superior performance in terms of Root Mean Square Error (RMSE) for RUL prediction compared to existing approaches.

The outcomes of our experiments highlight the effectiveness of our method, indicating its potential to significantly improve aviation engine maintenance procedures. This research contributes to the advancement of Prognostics and Health Management (PHM) approaches, providing a solid foundation for efficient maintenance scheduling and financial savings.
