# stackoverflow-search-engine-and-question-recommendation-using-nlp
This repository contains the code for full implementation of stack-overflow search engine and question recommendation.

# 1. Business/Real-world Problem
## 1.1 Introduction
## 1.2 Problem statement

# 2. Machine Learning Problem
## 2.1 Data
### 2.1.1 Data Overview
### 2.1.2 Data Field Explanation
## 2.2 Mapping the real-world problem to an ML problem
### 2.2.1 Type of Machine Learning Problem
### 2.2.2 Performance Metric
### 2.2.3 Real-world/Business objectives and constraints
### 2.2.4 Source/ Useful links

# 3. Exploratory Data Analysis
## 3.1 Data Loading
### 3.1.1 Parsing XML files and converting to pandas dataframe
### 3.1.2 Basic statistics and analysis
#### 3.1.2.1 Analysis on "Title" field
#### 3.1.2.2 Analysis on "Tags" field
#### 3.1.2.3 Analysis on "Topic" field
#### 3.1.2.4 Analysis on "Body" field
## 3.2 Data De-duplication and Cleaning
### 3.2.1 Removing datapints with null and duplicate title
### 3.2.2 Data Preprocessing for feature Title and Body
### 3.2.3 Data Preprocessing for feature Tags
### 3.2.4 Merging all Preprocessed data with dataframe
### 3.2.5 Saving final merged preprocessed dataframe

# 4. Feature Engineering
## 4.1 Description
## 4.2 Feature Engineering for textual feature
### 4.2.1 TF-IDF(Term Frequency - Inverse Document Frequency)
### 4.2.2 TF-IDF W2V using pre-defined glove_vectors
### 4.2.3 Word2Vec embedding from scratch
### 4.2.4 Distilbert embedding
### 4.2.5 Universal sentence encoder
## 4.3 Saving all embedded vectors
## 4.4 Loading all embedded vectors

# 5. Model for topic prediction
## 5.1 Splitting data into train and test
## 5.2 ML model
## 5.3 Random sanity check of ML model
## 5.4 Observation

# 6. Spell correction for searched text

# 7. Few useful utility functions

# 8. Search Engine

# 9. Evaluation

# 10. Conclusion
