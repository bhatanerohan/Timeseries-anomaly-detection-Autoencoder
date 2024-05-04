
# Time Series Anomaly Detection Using Convolutional Autoencoders

## Introduction
This project demonstrates the use of a convolutional autoencoder model to detect anomalies in time series data. The approach is applied to the [Numenta Anomaly Benchmark (NAB)](https://www.kaggle.com/boltzmannbrain/nab) dataset, which contains artificially generated time series data with labeled anomalous periods of behavior.

## Setup
Before running the notebook, ensure you have the necessary libraries installed:
- Numpy
- Pandas
- Keras
- Matplotlib

You can install the required packages using the following command:
```
pip install numpy pandas keras matplotlib
```

## Data
The data used in this project are from two CSV files:
- `art_daily_small_noise.csv`: Contains normal (non-anomalous) time series data used for training the model.
- `art_daily_jumpsup.csv`: Contains time series data with sudden jumps (anomalies) used for testing the model.

These files are hosted on GitHub and are accessed directly within the notebook.

## Model
The model built is a convolutional autoencoder, which learns to reconstruct the normal time series data. During testing, it tries to reconstruct new data and the reconstruction error is measured. Higher errors indicate anomalies.

## Usage
To run this notebook:
1. Clone the repository or download the files.
2. Open the Jupyter Notebook in an environment that supports Python and Jupyter (like Anaconda or JupyterLab).
3. Run the notebook cells sequentially to see the output and anomaly detection results.

## Contributing
Contributions to this project are welcome. You can suggest improvements or add new features by opening an issue or submitting a pull request.

## License
This project is open-sourced under the MIT license.

---

Enjoy testing and improving your anomaly detection model!
