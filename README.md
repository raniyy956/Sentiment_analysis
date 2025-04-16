
#  Sentiment Analysis on Women's E-Commerce Clothing Reviews

This project performs sentiment analysis on real-world customer reviews of women’s e-commerce clothing. It combines **machine learning** with **Power BI visualizations** to provide actionable insights into customer feedback.



# Problem Statement

Businesses need to understand customer sentiments in reviews to improve product offerings and customer satisfaction. This project analyzes customer sentiments using machine learning techniques and presents interactive insights through Power BI.

# Key Objectives

- Predict customer sentiment from review texts using ML models.
- Explore the relationship between sentiments, ratings, and product categories.
- Create a Power BI dashboard for visual storytelling and business insights.

---

# Project Structure

#  Technologies Used

- Python (Pandas, Scikit-learn, NLTK, Seaborn, Matplotlib)
- Power BI for dashboard creation
- Jupyter Notebook for experimentation


# Machine Learning Workflow

1. Text Preprocessing
   - Tokenization, Stopword Removal
2. Feature Engineering  
   - Sentiment labels (positive, negative, neutral)
   - Categorical transformations
3. Modeling
   - Logistic Regression
   - Random Forest Classifier
4. Evaluation 
   - Accuracy, F1-Score, Confusion Matrix


## 📈 Power BI Dashboard Highlights

- **Sentiment distribution by rating**
- **Most reviewed product categories**
- **Word cloud of top sentiments**
- **Interactive slicers for product and sentiment filtering**

---


## 📉 Results

- Best model: **Logistic Regression**, with accuracy of  0.8211
- Clear correlation between review length and sentiment polarity
- Insightful trends revealed using Power BI visuals

---


## 🔍 Future Improvements

- Deploy model with a simple web app (e.g., Streamlit or Flask)
- Add more complex NLP models like BERT
- Automate the Power BI refresh with live data

---


## 📎 Resources

- [Dataset on Kaggle](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews)
- Power BI file included in this repo
