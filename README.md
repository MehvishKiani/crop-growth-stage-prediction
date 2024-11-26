# crop-growth-stage-prediction
This project aims to predict the growth stage of crops using various environmental factors such as nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall. The models included are implemented using different machine learning algorithms: TensorFlow (Deep Learning), scikit-learn (Traditional ML), and RandomForest.
## Dataset
The dataset used in this project is the "Crop Recommendation Dataset", which contains features related to soil and environmental conditions and the crop growth stage labels.

## Models
1. **TensorFlow (Deep Learning)**: A neural network-based model to predict crop growth stages.
2. **scikit-learn (ML Algorithms)**: A collection of traditional machine learning models for crop classification.
3. **RandomForest**: An ensemble model that uses a collection of decision trees for predicting crop growth stages.

## Files
- `tensorflow_model.py`: Implements the deep learning model for growth stage prediction using TensorFlow/Keras.
- `scikit_learn_model.py`: Implements machine learning models like SVM, KNN, etc., for growth stage prediction.
- `random_forest_model.py`: Implements the Random Forest model for predicting crop growth stages.

## Features
- **Data Preprocessing**: The dataset is cleaned, missing values are handled, and categorical labels are encoded.
- **Model Training**: The models are trained using the crop dataset and validated using a test set.
- **Prediction**: The trained models can predict the growth stage of crops based on new input features.

## Requirements
The following libraries are required to run the models:
- `tensorflow==2.x`
- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib`

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MehvishKiani/crop-growth-stage-prediction.git

   License
This project is licensed under the MIT License
