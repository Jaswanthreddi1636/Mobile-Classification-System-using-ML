# Mobile Price Classification - Capstone Project
# Author Reddi Jaswanth Kumar

This project focuses on classifying mobile phone price ranges based on various technical specifications using machine learning techniques.

## Project Overview
The goal of this analysis is to determine the price range (0: Low Cost, 1: Medium Cost, 2: High Cost, 3: Very High Cost) of mobile phones by analyzing features such as battery power, RAM, internal memory, camera specifications, and connectivity.

## Dataset Features
The dataset includes the following key features:
* **Battery Power**: Total energy a battery can store in one time measured in mAh.
* **RAM**: Random Access Memory in Megabytes.
* **Internal Memory**: Internal Memory in Gigabytes.
* **Camera**: Front (fc) and Primary (pc) camera megapixels.
* **Screen**: Screen height (sc_h) and width (sc_w) in cm.
* **Connectivity**: Support for 4G, 3G, Wi-Fi, Dual SIM, and Bluetooth.
* **Processor**: Clock speed and number of cores.

## Tech Stack
* **Language**: Python
* **Environment**: Google Colab / Jupyter Notebook
* **Libraries**: 
    * `pandas` & `numpy`: Data manipulation and analysis
    * `seaborn` & `matplotlib`: Data visualization
    * `scikit-learn`: Machine learning modeling (assumed based on standard Capstone workflow)

## Project Structure
* `Capstone.ipynb`: The main notebook containing Exploratory Data Analysis (EDA) and model development.
* `train.csv`: Training dataset containing the target `price_range`.
* `test.csv`: Test dataset for evaluating model performance.

## How to Run
1. Clone this repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
