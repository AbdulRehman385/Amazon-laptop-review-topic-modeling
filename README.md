# Amazon Laptop Reviews: Topic Modeling Project

### Introduction
In today's fast-paced world, choosing the right laptop can be overwhelming with endless features, specifications, and user reviews to consider. To simplify this process, we performed **Topic Modeling** on a dataset of **Amazon Laptop Reviews** using **Latent Dirichlet Allocation (LDA)**.

This project uncovers the main themes/topics in the reviews to identify recurring feedback and patterns that can help customers make informed decisions.

---

### Dataset
The dataset was downloaded from **Kaggle**:  
- **Dataset Name**: Amazon Laptop Review  
- **Source**: [Ashwinishet on Kaggle](https://www.kaggle.com/ashwinishet/amazon-laptop-review)

---

### Project Workflow
The following steps were performed in the notebook:

1. **Data Collection**
   - Imported the dataset from Kaggle.  
   - Unzipped and loaded the data into the project environment.

2. **Data Preprocessing**
   - Cleaned and tokenized the text data.  
   - Removed stopwords, punctuation, and irrelevant content.  

3. **Topic Modeling**
   - Implemented **Latent Dirichlet Allocation (LDA)** using libraries such as `Gensim` and `sklearn`.  
   - Extracted dominant topics from the review data.

4. **Topic Visualization**
   - Visualized the identified topics and their associated keywords.  

---

### Technologies Used
- **Python**
- **Libraries**:
   - `pandas`  
   - `numpy`  
   - `matplotlib`  
   - `seaborn`  
   - `Gensim`  
   - `sklearn`  
   - `NLTK`  

---

### Project Outputs
1. Identified **key topics** from Amazon laptop reviews.  
2. Visualized the topic distribution and most relevant words for each topic.  
