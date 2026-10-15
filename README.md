# FreshGuard — Food Spoilage Prediction

## Project Overview
FreshGuard is a machine learning project that predicts whether food may be spoiled based on storage conditions.

## Objectives
- Predict food spoilage using tabular data.
- Compare multiple machine learning classification models.
- Build an interactive web interface using Gradio.

## Dataset Features
- Fruit
- Temperature
- Humidity
- CO2 concentration
- Storage duration (Days)
- Target variable: Spoiled (Yes/No)

## Machine Learning Models
1. Decision Tree Classifier
2. Random Forest Classifier
3. Support Vector Machine (SVM)

## Best Initial Result
The Decision Tree achieved 75.51% accuracy on the initial test split. Results may vary with different data splits.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Gradio
- Google Colab

## How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Upload `Dataset.csv` to the Colab session.
3. Run the notebook cells in order.
4. Launch the Gradio interface to test predictions.

## Disclaimer
This is an educational prototype. Predictions are not a substitute for food-safety testing.

