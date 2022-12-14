# Portfolio Projects
A collection of data science projects to demonstrate knowledge and skills.


## 1. [Classifying Plant Images with a Convolutional Neural Network](https://colab.research.google.com/github/rfraissinet/portfolio_projects/blob/main/CNN_Plant_Classification.ipynb)
- **Goal**: To build a convolutional neural network to classify images of plant seedlings for crop management.
- **Outline**:
  - Imported and pre-processed images for model buildling
  - Built an initial CNN as a baseline to measure performance changes
  - Created a function to iterate model creation to overcome inconsistencies in accuracy
  - Used Data Augmentation, Batch Normalization, and Dropout techniques and assessed performance changes
  - Compared all five models and selected the best for future development
  - Suggested ideas for improvement
- **Key skills**: Python (Keras, TensorFlow, scikit-learn), Neural Networks, Computer Vision, Image Classification, Image Manipulation

## 2. [Predicting Airline Tweet Sentiment](https://colab.research.google.com/github/rfraissinet/portfolio_projects/blob/main/Predicting_Airline_Tweet_Sentiment.ipynb)
- **Goal**: To build a random forest model that predicts airline tweet sentiment based on text content.
- **Outline**:
  - Imported dataset and made observations about missing values
  - Explored the data to understand sentiment distributions, text content, and timing and location variables
  - Performed text processing including the removal of unnecessary characters, tokenization, and lemmatization
  - Created a predictive model with Count Vectorizer and Random Forest
  - Created a predictive model with TF-IDF and Random Forest
  - Analyzed and compared findings from both models
  - Provided insights and recommendations, gave ideas for improvement
- **Key skills**: Python (BeautifulSoup, NLTK, scikit-learn), Natural Language Processing, Sentiment Analysis, Vectorization (Count Vectorizer and TF-IDF)

## 3. [Bagging and Boosting to Expedite Visa Approval](https://nbviewer.org/github/rfraissinet/portfolio_projects/blob/main/Bagging_and_Boosting_to_Expedite_Visa_Approval.ipynb)
- **Goal**: To facilitate the visa application review process by creating a machine learning model that shortlists potential candidates.
- **Outline**:
  - Explored a dataset of visa applications using visualizations to make observations
  - Cleaned the data to prepare for model building
  - Built and tuned several bagging and boosting models to make predictions
  - Identified important features and created a suitable candidate profile
  - Provided insights and recommendations
- **Key skills**: Python (Seaborn, scikit-learn), Data Preprocessing, Bagging (Bagging & Random Forest), Boosting (AdaBoost, Gradient Boosting, XGBoost), Hyperparameter Tuning with GridSearchCV

## 4. [Clustering Stocks for Short-term and Long-term Investment](https://nbviewer.org/github/rfraissinet/portfolio_projects/blob/3d3fec9202c1e52c2c834823ce774f20e617223a/Clustering_Stocks.ipynb)
- **Goal**: To categorize stocks for different investment approaches with the use of clustering algorithms.
- **Outline**:
  - Explored a dataset of stocks using summary statistics and visualizations to make observations
  - Used K-means and Hierarchical Clustering algorithms to group stocks into clusters
  - Created cluster profiles and provided insight on each cluster
  - Compared the efficacy and usability of both algorithms
  - Distilled findings and gave stock recommendations
- **Key skills**: Python (Seaborn, scikit-learn, SciPy), Data Visualization, K-means Clustering, Hierarchical Clustering, Cluster Profiling

## 5. [Scraping TSA Data to Determine Best Times to Travel](https://nbviewer.org/github/rfraissinet/portfolio_projects/blob/main/Scraping_TSA_Data.ipynb)
- **Goal**: To identify airline travel trends by scraping and visualizing TSA checkpoint data.
- **Outline**:
  - Extracted HTML data from TSA's website and parsed the values into a workable format
  - Organized the values into a Pandas dataframe
  - Visualized travel numbers across multiple time frames
  - Identified trends and presented possible explanations
  - Proposed several possible timing approaches to avoid busy travel days
- **Key skills**: Python (BeautifulSoup, NumPy, pandas, Matplotlib, seaborn), Web Scraping, Data Visualization

## 6. [A "MuSQL" Analysis](https://nbviewer.org/github/rfraissinet/portfolio_projects/blob/main/A_MuSQL_Analysis.ipynb)
- **Goal**: To analyze an online music store's database using SQLite.
- **Outline**:
  - Imported SQL and relevant database into Jupyter Notebook
  - Created a frequency table for genres
  - Viewed employee performance across a few sales metrics
  - Computed and displayed sales metrics by country
  - Summarized findings
- **Key skills**: SQL
