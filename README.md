
# Resume Ranker 
![712c1697-4692-4bdb-802a-26b27d5a936d](https://github.com/Sanjay2004046/Resume-ranker-using-ML/assets/111832913/d5598ced-35b8-4660-86dd-b79b23febf08)

## Overview
This project, "Recruitment-Filtration-for-Enterprises-using-ML-model" leverages Natural Language Processing (NLP) techniques to evaluate the relevance of resumes to a provided job description. The main script, resumeparserfinal.ipynb, handles data preprocessing, feature engineering, and model training. Employing TF-IDF cosine similarity and a Random Forest Regressor, resumes are scored to aid in the recruitment process. Sample data is available in Resume_Ranking_Data_Set.csv, and a sample job description is provided in Job_Description.txt. The project structure ensures clarity and simplicity. The Gradio interface enables users to upload job descriptions and receive the top 10 matching resumes along with their scores. Overall, the project streamlines the resume ranking process in recruitment scenarios.

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


## Directory Structure
        
    ├── Resume Ranker
    │   ├── Job Description.txt   
    |   ├── resume-ranker.ipynb
    │   └── dataset.csv                  
 
 ## OneAPI Optimization

This project has been optimized using the [OneDAL](https://OneDAL.com/) library, a powerful and efficient tool for accelerating data processing tasks. OneDAL provides a seamless integration of various APIs, simplifying the implementation of complex operations.

### OneDAL Integration

The project leverages the OneDAL library to enhance the efficiency of data processing, particularly in the context of resume ranking. OneDAL's API integration streamlines tasks, reducing computational overhead and improving overall performance.

### Benefits of OneDAL

- *Accelerated Processing:* OneDAL's APIs significantly speed up data-related operations, ensuring faster execution of tasks.
- *Resource Optimization:* The library optimizes resource usage, resulting in improved performance without compromising accuracy.
- *Ease of Implementation:* Integrating OneDAL APIs into the project was seamless, providing a user-friendly solution for enhanced functionality.

### How to Integrate OneDAL

To incorporate OneDAL into your project, follow these steps:

1. Visit [OneDAL](https://OneDAL.com/) and sign up for an account.
2. Obtain API keys from OneDAL for the desired functionality.
3. Update the project code to include the OneDAL API calls, taking advantage of the library's capabilities.

Feel free to explore the full range of OneDAL's features to further optimize your project and elevate its performance.
![WhatsApp Image 2024-01-27 at 12 05 24 PM](https://github.com/Arjun-A3/Recruitment-Filtration-for-Enterprises-using-ML-model/assets/110415386/98bb730a-2124-4a79-9a34-6b224a133bd3)



## Results
The Gradio interface provides an interactive way to upload job descriptions and receive the top 10 matching resumes along with their scores.

![App Screenshot](https://github.com/Arjun-A3/Recruitment-Filtration-for-Enterprises-using-ML-model/blob/main/result/WhatsApp%20Image%202024-01-27%20at%2011.42.42%20AM.jpeg)

https://github.com/Arjun-A3/Recruitment-Filtration-for-Enterprises-using-ML-model/assets/110415386/4dd3d2f7-1c08-4762-9e22-245dc83dffb2



## Acknowledgments
The project uses the Gradio library for creating an interactive interface.
Special thanks to the contributors and maintainers of the open-source libraries used in this project.




