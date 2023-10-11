# ML_Project_2023
Machine Learning project for CS-C3240 - Machine Learning D, 4.9.2023-13.10.2023

Overview

This project focuses on sentiment analysis using two different machine learning models: Logistic Regression and Multilayer Perceptron (MLP) Classifier. The goal is to predict the sentiment (positive, neutral, or negative) of text data.

![bothmethods](https://github.com/MariusBoda/ML_Project_2023/assets/35667954/54120843-06cb-4c2b-8a3f-08490c02bf66)

Project Structure

The project is organized as follows:

Data Preprocessing: The dataset is loaded from a CSV file, and data preprocessing steps include cleaning, handling missing values, and transforming the sentiment column.

Model Training: Two models, Logistic Regression and MLP Classifier, are trained on the preprocessed data. The data is split into training, validation, and test sets. The models are evaluated using metrics such as accuracy, log loss, and classification reports.

Model Comparison: A comparison between the performance of the Logistic Regression and MLP Classifier models is provided, highlighting their strengths and weaknesses.

Confusion Matrix Visualization: The confusion matrix is visualized using seaborn and matplotlib to provide insights into model performance across different sentiment classes.

Sentiment Analysis Function: A function for sentiment analysis is included, allowing users to input text and receive the predicted sentiment using the trained models.

Usage

Install Dependencies:
    Ensure that the required Python libraries are installed. You can install them using the following command:

    pip install numpy pandas matplotlib seaborn scikit-learn

Run the Jupyter Notebook:
    Open the Jupyter Notebook provided in the project. Execute each cell sequentially to load the data, preprocess it, train the models, and evaluate their performance.

Explore Model Performance:
    Analyze the metrics reported for both models on the validation and test sets. Gain insights into how each model performs on different sentiment classes.

Sentiment Analysis Function:
    Use the provided sentiment analysis function to analyze the sentiment of custom text inputs. Experiment with different text inputs to observe how the models classify sentiment.

Future Improvements

Hyperparameter Tuning: Experiment with hyperparameter tuning for both models to optimize their performance further.

Ensemble Models: Explore the possibility of combining predictions from multiple models to improve overall accuracy.

Enhanced Visualizations: Extend the visualization section to include additional plots, such as learning curves or feature importance.

License

This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

Special thanks to the open-source community for providing valuable tools and libraries used in this project.

Feel free to customize this README to suit your project's specific details and requirements!
