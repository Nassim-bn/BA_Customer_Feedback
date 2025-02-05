# ✈️ Web scraping to gain company insights and predicting customer buying behaviour 

## 📌 Project Overview


## 📊 Steps Followed

## Task One : Web scraping to gain company insights¶

### **1️⃣ Scraping data from Skytrax**
- Scraping the data from [https://www.airlinequality.com/airline-reviews/british-airways]
- Loaded the dataset using Pandas.

### **2️⃣ Data Cleaning & Preprocessing**
- Remove unnecessary characters (special symbols, URLs, etc.).
- Convert text to lowercase for uniformity.
- Remove stopwords (common words like "the", "is", "and").
- Tokenization (split sentences into words).
- Lemmatization (convert words to their base form).

### **3️⃣ Sentiment Analysis**
- Perorm sentiment analysis to determine whether the review is positive, negative, or neutral.
- Distribution of Sentiment: What percentage of reviews are positive, negative, or neutral?
- Visualize Sentiment Distribution : A quick bar chart will help to visualize the sentiment labels.

## Task Two : Predicting customer buying behaviour


### **1️⃣ Exploratory data analysis (EDA)**
- Explore the data in order to better understand what we have and the statistical properties of the dataset.
- Removed unnecessary columns.
- Scaled numerical data for better model efficiency.
Data visualization**
- Implemented **Linear Regression** as a baseline model.

### **2️⃣ Data visualization**
-  Histogram for numerical variables like num_passengers, purchase_lead, etc.
- Bar plot for categorical variables like sales_channel, trip_type.


### **3️⃣ Data Preprocessing**
- Handling missing values
- Encode Categorical Variables

### **3️⃣ Evaluating model and present findings**
- Train the model
- Evaluate how well it performed by conducting cross-validation and outputting appropriate evaluation metrics.

  
  
## 🛠 Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)
- **Jupyter Notebook** for structured analysis and visualization
- **BeautifulSoup** to collect all the links to the reviews and then to collect the text data on each of the individual review links.

## 📂 Project Structure
```
📦 BA_Customer_Feedback  
 ┣ 📦 BA_Model_Prediction  
  ┣ 📜 BA_model_prediction.ipynb  # Jupyter Notebook containing the analysis and predictive models  
  ┣ 📜 customer_booking.csv       # Dataset used for training  
  ┣ 📜 BA_Presentation_2.pdf      # Presentation (PDF) summarizing model performance results  
 ┣ 📦 Web_Scraping_Data  
  ┣ 📜 British_Airways_Web_Scraping.ipynb  # Jupyter Notebook for web scraping  
  ┣ 📜 BA_reviews.csv                       # CSV file containing the scraped data  
  ┣ 📜 BA_Presentation_1.pdf                # Presentation (PDF) summarizing insights from the scraped data  
 ┣ 📜 README.md  # Project documentation  

```

## 📌 Future Improvements
- Address class imbalance (e.g., SMOTE or class weighting).
- Enhance Class 1 recall by tuning hyperparameters or exploring other models (e.g., Gradient Boosting).
- Implement cross-validation and feature engineering for further improvements.

---
### 🏆 Author: Nassim BENCHIKH
