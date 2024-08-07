
---

# Deep Learning Model for Audio Compression

This repository contains Jupyter Notebooks and associated files for a deep learning-based audio compression project. The project involves data preprocessing, training an autoencoder model, and evaluating its performance on audio data.

## Repository Structure

- **`01_data_preparation_and_training.ipynb`**: This notebook includes the code for preprocessing and preparing the audio data for model training and  contains the code to train the autoencoder model for audio compression.
- **`02_model_evaluation.ipynb`**: This notebook is used to evaluate the performance of the trained model on test data, including metrics such as MSE, SNR, and RMS.
- **`requirements.txt`**: A file listing the Python dependencies required for the project.

## Dataset

The dataset used for this project is available at [Microsoft Scalable Noisy Speech Dataset (MS-SNSD)]([https://github.com/microsoft/MS-SNSD]).
https://github.com/microsoft/MS-SNSD


## Installation

To set up the environment for this project, install the necessary dependencies using the `requirements.txt` file. Run the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. **Data Preparation and Training**:
   - Open `01_data_preparation_and_training.ipynb`.
   - Follow the instructions to download the dataset from [Microsoft Scalable Noisy Speech Dataset (MS-SNSD)]([https://www.microsoft.com/en-us/research/project/ms-snsd/](https://github.com/microsoft/MS-SNSD)).
   - Add the correct path to the downloaded dataset in the notebook.
   - Change the path in the notebook where the model will be saved after training.
   - Run the cells to preprocess the audio data.
   - Then Execute the cells to train the autoencoder model on the preprocessed data.

2. **Model Evaluation**:
   - Open `model_evaluation.ipynb`.
   - Follow the instructions to upload an audio file for evaluation.
   - Specify the correct path to load the trained model.
   - Run the cells to evaluate the performance of the trained model using various metrics.

## Results

The evaluation notebook will generate and display metrics such as Mean Squared Error (MSE), Signal-to-Noise Ratio (SNR), Peak Signal-to-Noise Ratio (PSNR), Structural Similarity Index (SSIM), and Root Mean Square Error (RMS) for the audio compression. Additionally, it will compare the original audio with the reconstructed audio, and you can play both to listen to the difference.

---
