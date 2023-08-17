# Mobile Price Prediction

This project demonstrates a mobile price prediction model using four classification algorithms: Random Forest, Gaussian Naive Bayes, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM). The aim is to predict the price range of mobile phones based on various features and specifications.

## Introduction

Mobile phones come in various price ranges and specifications. Accurate price prediction is essential for effective consumer strategy and market success. This project focuses on building a machine learning model that predicts the price range of mobile phones based on their features.

## Features

The dataset contains the following features:

- Battery Power in mAh
- Has Bluetooth or not
- Microprocessor clock speed
- Dual SIM support
- Front Camera Megapixels
- Has 4G support or not
- Internal Memory in GigaBytes
- Mobile Depth in Cm
- Weight of Mobile Phone
- Number of cores in the processor
- Primary Camera Megapixels
- Pixel Resolution height
- Pixel resolution width
- RAM in MB
- Mobile screen height in cm
- Mobile screen width in cm
- Longest time after a single charge
- 3G support or not
- Has touch screen or not
- Has Wi-Fi or not

## Methodology

1. Data Analysis: Examine data using statistical methods to identify meaningful information.

2. Data Preprocessing: Clean the data, handle missing values, and convert non-numeric data into numerical format using one-hot encoding.

3. Model Building: Train classification algorithms (Random Forest, Gaussian NB, KNN, SVM) on the preprocessed data.

4. Model Evaluation: Evaluate the models' accuracy using confusion matrices and other metrics.

## Requirements

- Python (>=3.6)
- scikit-learn
- seaborn
- matplotlib

## Usage

1. Clone this repository:
   ```
   [git clone https://github.com/yourusername/mobile-price-prediction.git](https://github.com/Sanmuga/Mobile-price-prediction.git)
   cd mobile-price-prediction
   ```

2. Install the required libraries:
   ```
   pip install scikit-learn seaborn matplotlib
   ```

3. Update the file path in the code to point to the 'train.csv' dataset.

4. Run the main script:
   ```
   python mobile_price_prediction.py
   ```

5. The script will display accuracy scores and confusion matrices for each classifier.

## Results

The accuracy scores and confusion matrices for each classifier are displayed in the console. The SVM classifier achieves the highest accuracy among the four classifiers.

## Author

Sanmugavadivel K
sanmugavadivel23@gmail.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
