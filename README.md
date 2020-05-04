# Price-Prediction-in-E-Commerce
This repo will guide you through the basic analysis, EDA and the prediction in the Mercary Price Prediction challenge. 

**What the project is about?**

The main objective of this project is to handle, explore, analyze the natural-language (English) data and predict the price of the products for an e-commerce named 'Mercari'. The problem statement is as follows and copied directly from Kaggle. 

Product pricing gets harder at scale, considering just how many products are sold online. Clothing has strong seasonal pricing trends and is heavily influenced by brand names, while electronics have fluctuating prices based on product specs.

Mercari, Japan’s biggest community-powered shopping app, knows this problem deeply. They’d like to offer pricing suggestions to sellers, but this is tough because their sellers are enabled to put just about anything, or any bundle of things, on Mercari's marketplace.

**What is the task?**

The task is to build an algorithm that automatically suggests the right product prices. We were provided with user-inputted text descriptions of their products, including details like product category name, brand name, and item condition.

**What action did I take?**

To predict the price, I had to tackle the problem following the standard data science pipelines. I cleaned the noisy data, analyze them, visualized the distribution when necessary, performed feaure engineering, and cross validated the performance using different machine learning algorithms. The actions were well described and demonstrated in the codes. 

#### Codes ####

* 01_basic_data_analysis_and_visulization.ipynb: The task of the code can be subdivided in following groups:

  - ETLing the data from source
  - setting up the environment
  - Wrangling the data
  - Perform basic descriptive analysis from the features
  - Provide necessary visualization for the price distribution in many cases
  - Subdividing the groups if needed
  - Analyzing individual features and see if there's any effect
  
 * 02_NLP_analysis_and_visualization.ipynb: The main tasks are;
 
   - Analyzing the natural-language-features in simplest way
   - Which normalizations should we do for the NLP purposes and is there any effect?
   - Using the standard techniques like bag-of-words and n-grams, and also using word-embedding techniques like count vectorizer and tf-idf to vectorize the text features.
   - Visualization of performance with defferent NLP techniques.
   
  * 03_prediction_and_performance_comparison.ipynb: This code mainly wraps up some knowledge from the previous codes and performs prediction:
  
    - Summurizing the knowledge from our EDA. 
    - Perform all necessary feature transformation to perform machine learning algorithms.
    - Treat the problem as regression and using ridge and lasso to decide what to use.
    - Use Light GBM to compare the performance.
    - Build an ensemble model with Light GBM and Ridge regression and compare the performance. 
    
 
 

 





