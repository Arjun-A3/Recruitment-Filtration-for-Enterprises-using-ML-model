
# Resume Ranker 

## Overview
his project, "Recruitment-Filtration-for-Enterprises-using-ML-model" leverages Natural Language Processing (NLP) techniques to evaluate the relevance of resumes to a provided job description. The main script, resumeparserfinal.ipynb, handles data preprocessing, feature engineering, and model training. Employing TF-IDF cosine similarity and a Random Forest Regressor, resumes are scored to aid in the recruitment process. Sample data is available in Resume_Ranking_Data_Set.csv, and a sample job description is provided in Job_Description.txt. The project structure ensures clarity and simplicity. The Gradio interface enables users to upload job descriptions and receive the top 10 matching resumes along with their scores. Overall, the project streamlines the resume ranking process in recruitment scenarios.

## Requirements
- Python 3.x
- Required Python libraries: pandas, numpy, nltk, scikit-learn, gradio

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Arjun-A3/Recruitment-Filtration-for-Enterprises-using-ML-model
   cd Recruitment-Filtration-for-Enterprises-using-ML-model


## Usage
 Prepare your dataset: Ensure you have a CSV file containing resume data. Columns like 'name', 'degree', 'links', and 'work_experience' are expected.

 Data Preprocessing: The script performs various data preprocessing steps, including handling missing values and extracting relevant information from the dataset.

 TF-IDF Cosine Similarity: Resumes are scored based on their similarity to a provided job description using TF-IDF cosine similarity.

 Model Training: The Random Forest Regressor is used to predict resume scores based on encoded features.

 Gradio Interface: Launch the Gradio interface to upload a job description file and get the top 10 matching resumes.

## File Structure
 |-- Resume-Ranker-Using-Random-Forest
    |-- resumeparserfinal.ipynb        # The main Python script for preprocessing, feature engineering, and model training.
    |-- Job_Description.txt            # Sample job description file used for scoring resumes.
    |-- Resume_Ranking_Data_Set.csv    # Sample CSV file containing resume data.

## Results
The Gradio interface provides an interactive way to upload job descriptions and receive the top 10 matching resumes along with their scores.

## Acknowledgments
The project uses the Gradio library for creating an interactive interface.
Special thanks to the contributors and maintainers of the open-source libraries used in this project.




