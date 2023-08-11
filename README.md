**Audio Surveillance System with CRNN and Intensity Vector**

**Overview:**
This repository contains code and information related to an advanced audio surveillance system that combines the Convolutional Recurrent Neural Network (CRNN) algorithm with the Intensity Vector method for real-time audio data analysis. The CRNN algorithm is used for audio signal classification, while the Intensity Vector method aids in sound event localization during feature extraction.

**Contents:**
- `CRNN.ipynb`: Jupyter Notebook featuring the implementation of the CRNN algorithm for audio signal classification. This notebook covers the architecture, training process, and evaluation metrics, including the achieved F-score.
- `Feature_Extraction.ipynb`: Jupyter Notebook focusing on feature extraction using the Intensity Vector method. This notebook explains how to extract temporal and spectral features from raw audio signals and calculate sound event locations through the Intensity Vector approach.
- `README.md`: This readme file, providing an overview of the project, its components, and instructions for replication.

**Usage:**
1. **Dataset:** Obtain the TAU-NIGENS Spatial Sound Events 2020 dataset from zenodo.org or any suitable source. You need a directory named `datasets/` to store this dataset, but as you mentioned you don't have the dataset directory, make sure you adjust the data loading parts in the notebooks accordingly.

2. **Feature Extraction:** Execute the `Feature_Extraction.ipynb` notebook before running `crnn.ipynb`. This notebook demonstrates how to extract temporal and spectral features from raw audio signals using the Intensity Vector method. It also calculates sound event locations for enhanced analysis.

3. **CRNN Implementation:** Access the `CRNN.ipynb` notebook using Jupyter Notebook or Google Colab. This notebook demonstrates how to construct, train, and evaluate the Convolutional Recurrent Neural Network for audio signal classification. The process includes data preprocessing, model construction, training, and evaluation.

**Results:**
The CRNN algorithm's performance is evaluated using the TAU-NIGENS dataset, and the Intensity Vector method's sound event localization accuracy is assessed. Combining these two techniques provides a comprehensive understanding of the system's effectiveness.

**Disclaimer:**
This repository and its contents serve as an advanced demonstration of an audio surveillance system integrating the CRNN algorithm with the Intensity Vector method. The conclusions drawn are based on the provided dataset and may not perfectly represent real-world scenarios. Users are encouraged to adapt and extend the code for their specific use cases and datasets.

