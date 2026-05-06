
# Social Media Behaviour & Mental Health Profiling

## Overview
This project applies unsupervised learning techniques to identify hidden patterns in social media usage behaviour and uncover potential mental health risk profiles. The analysis is performed without using any labelled clinical data, relying solely on behavioural indicators.

## Problem Statement
Many mental health conditions remain undiagnosed due to stigma, cost, and limited access to professionals. However, users generate large amounts of behavioural data through social media usage. This project aims to utilise that data to detect potential mental health risks early.

## Objectives
- Analyse social media usage behaviour
- Identify hidden user groups using clustering techniques
- Interpret clusters as mental health risk profiles
- Visualise patterns and relationships in the data

## Dataset
- Source: Kaggle  
- Dataset: Social Media & Mental Health  
- Type: Survey-based behavioural dataset  

The dataset includes features such as:
- Screen time
- Sleep-related issues
- Social comparison behaviour
- Validation seeking
- Emotional indicators (e.g., depression)

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- UMAP

## Methodology

### 1. Data Collection & Understanding
- Loaded dataset
- Checked missing values and data types
- Performed initial cleaning

### 2. Data Preprocessing & Feature Engineering
- Encoded categorical variables
- Scaled numerical features
- Selected relevant behavioural features

### 3. Dimensionality Reduction
- Applied UMAP to reduce high-dimensional data
- Visualised data in 2D and 3D

### 4. Clustering Models
- Applied K-Means clustering
- Applied Gaussian Mixture Model (GMM)
- Determined optimal clusters using:
  - Elbow Method
  - Silhouette Score

### 5. Analysis & Visualization
- Visualised cluster distributions
- Generated boxplots and distribution plots
- Analysed feature differences across clusters
- Interpreted clusters as risk levels:
  - Low Risk
  - Moderate Risk
  - High Risk

## Key Findings
- High screen time and sleep issues are strongly associated with higher risk clusters  
- Social comparison and validation seeking contribute to negative behavioural patterns  
- Clear separation of users into distinct behavioural groups was achieved  
- Unsupervised learning successfully identified meaningful patterns without labelled data  

## Conclusion
The project demonstrates that behavioural data from social media can be used to identify potential mental health risks. Clustering techniques revealed distinct user profiles, highlighting the importance of early detection through data-driven approaches.

## Real-World Implications
- Can support early mental health detection systems  
- Useful for social media platforms to identify at-risk users  
- Applicable in educational institutions for student wellbeing monitoring  
- Valuable in regions with limited access to mental health professionals  

## Limitations
- Based on self-reported survey data  
- No clinical labels for validation  
- Results depend on feature selection and clustering parameters  

## Future Work
- Use larger and more diverse datasets  
- Incorporate real-time behavioural data  
- Apply advanced models such as deep learning  
- Validate findings with clinical data  

## Ethical Considerations
- Ensure user privacy and data protection  
- Avoid misuse of behavioural data  
- Prevent misclassification risks  
- Use models as support tools, not diagnostic systems  

## How to Run
1. Open the project in Google Colab  
2. Upload or load the dataset  
3. Run all cells sequentially  
4. View visualisations and analysis outputs  

## Output
- Clustered dataset with risk labels  
- Visualisations of user behaviour  
- Insights into mental health patterns  

## Authors
Group Project – Unsupervised Learning