# Movie Recommendation System
## Project Description
This project aims to build a movie recommendation system using the IMDb Top 1000 dataset. It includes steps for data preprocessing, data visualization, and implementing recommendation systems. Additionally, Apriori algorithm analysis was performed using KNIME.

## Dataset
The dataset is obtained from Kaggle and contains information about the top 1000 films from IMDb. You can access the dataset here: https://www.kaggle.com/datasets/omarhanyy/imdb-top-1000

## Contents
Jupyter Notebook: Contains Python code for building the recommendation system, data preprocessing, and visualizations.
KNIME Workflow: Includes data analysis and application of the Apriori algorithm in KNIME.
Visualizations: Graphs showing the results of data analysis.
## Technologies Used
Python
Pandas
Scikit-learn
Matplotlib
Seaborn
KNIME Analytics Platform
Jupyter Notebook
## Steps
### 1. Data Preprocessing
Missing Values: Missing values have been checked and filled appropriately.
Data Cleaning: Commas and special characters have been cleaned.
Word Splitting: Texts in the Description column have been split into words.
### 2. Data Visualization
Genres: Distribution of movie genres has been visualized.
Directors: Distribution of the top directors by number of films has been displayed.
Movie Distribution: Visualizations of movie ratings and other features have been created.
### 3. Recommendation System
TF-IDF Vectorization: TF-IDF vectorization has been applied to the Genre column.
Similarity Calculation: Cosine similarity has been used to build the movie recommendation system.
### 4. KNIME Analysis
Apriori Algorithm: Association rules have been analyzed based on movie descriptions.
Data Processing: Data processing and analysis have been performed using KNIME.
## Screenshots
Visualization 1: ![Screenshot 2024-07-22 132902](https://github.com/user-attachments/assets/3d65a494-9797-4498-b0e8-8c2757609182)

Visualization 2: ![Screenshot 2024-07-22 132908](https://github.com/user-attachments/assets/80471a27-7c6d-4611-bb1b-b94bb4bd8625)

Visualization 3:![Screenshot 2024-07-22 132914](https://github.com/user-attachments/assets/0e096fec-d33d-4b03-abee-1f35955b4cbd)

Visualization 4: ![image](https://github.com/user-attachments/assets/960e44a3-0159-4548-a885-4828afdcdaed)

## Issues
### 1-Dataset have many repeteteive row

### 2-FP-Growth model take much time so I can't take result.

### 3-I didn't build this mdoel on Knime, So I try again.
