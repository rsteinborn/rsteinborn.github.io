# Cybersecurity Threat Detection

## Description

This project focuses on threat classification using machine learning models. It processes `.puml` files to extract features and predict potential security threats in system architectures.

## Key Features

- Processing of PlantUML (.puml) files for feature extraction
- Machine learning-based threat classification
- Streamlit application for uploading files and predicting threats
- Visualization of original and modified UML diagrams

## Technologies Used

- Python
- Jupyter Notebook
- Streamlit
- Machine Learning libraries (e.g., scikit-learn)
- PlantUML

## Project Structure

- `algorithm.ipynb`: Jupyter notebook for data preprocessing, model training, and evaluation
- `app.py`: Streamlit application for uploading `.puml` files and predicting threats
- `Streamlit.py`: Streamlit application for rendering and modifying PlantUML diagrams
- `saved_steps.pkl`: Pickle file containing the trained model and preprocessing steps

## Usage

To run the Streamlit app:

```bash
streamlit run app.py
```

Users can then:

1. Upload a `.puml` file
2. View the original and modified UML diagrams
3. Click the 'Predict' button to classify the threat

## Model Training

The model is trained using a pipeline with preprocessing steps and a classifier. Hyperparameter tuning is performed using GridSearchCV.

## Challenges and Solutions

One of the main challenges was accurately processing and extracting features from PlantUML files. This was addressed by developing custom preprocessing steps and feature extraction techniques.

## Future Improvements

- Enhance the feature extraction process for more complex UML diagrams
- Implement more advanced machine learning models
- Develop a more comprehensive threat classification system

## GitHub Repository

[Link to the project repository](https://github.com/rsteinborn/threat-modeler)

## License

This project is licensed under the MIT License.
