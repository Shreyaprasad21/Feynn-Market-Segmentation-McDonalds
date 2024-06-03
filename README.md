![1630642907522](https://github.com/Shreyaprasad21/FeynnLabs_McDonaldsCaseStudy/assets/142075353/db086bd1-87b7-4e9e-a908-65beb5915ff5)

# PROJECT - McDONALDS CASE STUDY
During my internship at Feynn Labs, I had the chance to analyze a detailed dataset from McDonald's, focusing on market segmentation and uncovering valuable consumer insights. Market segmentation enables businesses to divide their target market into distinct groups based on shared characteristics, preferences, and behaviors. By understanding these segments, companies can refine their marketing strategies to effectively engage with different consumer groups, thus improving overall brand performance.


## Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Dependencies](#dependencies)
4. [Usage](#usage)
5. [File Structure](#file-structure)
6. [Deployment](#deployment)
7. [Notes](#notes)

## Introduction
The Multiple Disease Detection System is designed to detect Parkinson's disease, diabetes, and heart disease from medical images using advanced deep learning techniques. The system aims to assist healthcare professionals by providing an automated tool that can quickly and accurately diagnose these conditions, thereby improving the efficiency and effectiveness of medical diagnoses. The project leverages state-of-the-art machine learning algorithms to analyze medical data and identify potential diseases, offering a reliable solution for early detection and treatment planning. The application was deployed using Streamlit, an open-source app framework, which allows for the creation of interactive and shareable web applications for machine learning and data science.

## Features
- **Multi-Disease Detection:** Capable of predicting Parkinson's disease, diabetes, and heart disease from medical images.
- **Deep Learning Integration:** Utilizes advanced deep learning techniques to analyze medical images and make accurate predictions.
- **User-Friendly Interface:** Provides a simple and intuitive interface for users to upload medical images and receive disease predictions.
- **Real-Time Prediction:** Offers real-time prediction of diseases, enabling quick decision-making for healthcare professionals.
- **Scalability:** Designed to handle large volumes of medical data and can be easily scaled to include additional diseases in the future.
- **Streamlit Deployment:** Deployed using Streamlit, allowing for easy sharing and access to the disease detection system through a web browser.
- **Interpretability:** Provides explanations or visualizations to help users understand how predictions are made, increasing trust and transparency.
- **Model Performance Metrics:** Reports performance metrics such as accuracy, precision, recall, and F1-score to evaluate the reliability of predictions.
- **Continuous Improvement:** Allows for continuous improvement through feedback mechanisms, ensuring the system stays up-to-date with the latest medical research and advancements.

## Dependencies
- Python 3.9 or higher
- NumPy
- pandas
- scikit-learn

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/Shreyaprasad21/Project-3-AI-ML-Series-Multiple-Disease-Detection-system.git

2. Install dependencies:
   ```sh
   pip install -r requirements.txt

3. Run the desired disease prediction script:
- For Parkinson's Disease:
  ```
  parkinsons.ipynb
  ```
- For Diabetes:
  ```
  diabetes.ipynb
  ```
- For Heart Disease:
  ```
  heart.ipynb
  ```
  
4. Follow the prompts to input data for prediction.

## File Structure
- `parkinsons.ipynb`: Script for predicting Parkinson's Disease.
- `diabetes.ipynb`: Script for predicting Diabetes.
- `heart.ipynb`: Script for predicting Heart Disease.
- `Dataset/`: Directory containing the datasets for each disease.
- `parkinsons.csv`: Dataset for Parkinson's Disease.
- `diabetes.csv`: Dataset for Diabetes.
- `heart.csv`: Dataset for Heart Disease.
- `README.md`: Instructions and information about the project.

## Deployment
The project was deployed using Streamlit. To deploy the application locally:

1. Ensure Streamlit is installed:
  ```
  pip install streamlit
  ```

2. Run the Streamlit app:
  ```
  streamlit run app.py
  ```

3. Open your web browser and go to `http://localhost:8501`.

## Notes
- The project was developed using Jupyter Notebook, with separate notebooks (`parkinsons_detection.ipynb`, `diabetes_detection.ipynb`, `heart_disease_detection.ipynb`) for each disease.
- Each notebook contains the code for data preprocessing, model training, and evaluation specific to the respective disease.
- The datasets (`parkinsons.csv`, `diabetes.csv`, `heart_disease.csv`) are provided in the `Dataset/` directory.
- Model deployment, user interface, and interaction were implemented using Streamlit, providing an intuitive web interface for disease prediction.













# McDonald's Case Study Replication

## Description:
This project replicates a McDonald's case study using Python. It involves data preprocessing, PCA for dimensionality reduction, KMeans clustering for segment identification, segment profiling, and decision tree classification for marketing segmentation.

## Project Structure:
- `mcdonalds.csv`: Dataset containing customer feedback on McDonald's products.
- `FeynnLabs_Shreya_Prasad.ipynb`: Jupyter Notebook containing Python code for replication.
- `README.md`: Description of the project.
  

## Instructions:
1. Install Python and required libraries.
2. Open and run `FeynnLabs_Shreya_Prasad.ipynb` in a Jupyter Notebook environment.
3. Follow the code step-by-step to replicate the McDonald's case study.
4. Ensure the dataset `mcdonalds.csv` is in the correct directory.
