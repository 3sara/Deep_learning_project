# Deep_learning_project
This repository is organized as follows:

- [`data/`](data/): folder containing all dataset of images and weather data
- [`models/`](models/): folder containing all the saved and trained models
- [`plots/`](plots/): folder containing saved plots
- [`utility/`](utility/): folder containing useful notebooks for preprocessing and estraction of images

- `2dcnn_noweek_NT.ipynb`:
  - model architecture: 2D CNN for image processing, FC for prediction on data and precessed images.
  - data: Single day learning

- `2dcnn_rnn.ipynb`:
    - model architecture: 2D CNN for image processing, RNN for data processing, FC for prediction on both.
    - data: Multiple day learning, n° of channels manages both days and RGB

- `3dcnn_rnn.ipynb`:
    - model architecture: 3D CNN for image processing, RNN for data processing, FC for prediction on both.
    - data: Multiple day learning

- `3dcnn_lstm_rnn.ipynb`:
    - model architecture: 3D CNN and LSTM for image processing, RNN for data processing, FC for prediction on both.
    - data: Multiple day learning
    
-  `lstm_rain_forecast.ipynb`:
    - model architecture: LSTM for data processing
    - data: weather data from csv

-  `rnn_rain_forecast.ipynb`:
  - model architecture: RNN for data processing
  - data: weather data from csv

- `stagione.ipynb`:
  - model architecture: 2D CNN for image processing, FC for prediction on data and precessed images.
  - data: Single day learning, data only from the same season
