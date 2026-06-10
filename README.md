# 🎬 BERT-Based Sentiment Analysis and Aspect-Based Sentiment Analysis on IMDb Reviews

## 📌 Project Description

This project focuses on analyzing movie reviews from the IMDb dataset using BERT (Bidirectional Encoder Representations from Transformers), a state-of-the-art Natural Language Processing (NLP) model developed by Google.

The objective is to classify movie reviews into positive and negative sentiments and further perform Aspect-Based Sentiment Analysis (ABSA) to identify sentiments related to specific movie aspects such as acting, direction, screenplay, story, music, cinematography, and visual effects.

By leveraging the power of BERT, the model achieves high accuracy in understanding contextual meanings within reviews and provides detailed sentiment insights at both review and aspect levels.

---

## 🎯 Objectives

* Build a sentiment analysis model using BERT.
* Classify IMDb movie reviews as positive or negative.
* Extract important aspects from movie reviews.
* Perform aspect-level sentiment classification.
* Compare sentiment analysis performance before and after aspect filtering.
* Visualize sentiment trends and model performance.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* PyTorch
* Hugging Face Transformers
* BERT Model
* Natural Language Processing (NLP)

---

## 📂 Dataset

The project uses the IMDb Movie Reviews Dataset containing:

* Movie Title
* Review Text
* User Rating
* Sentiment Labels
* Review Metadata

---

## ⚙️ Project Workflow

### 1. Data Collection

* Load IMDb movie review dataset.
* Inspect data structure and features.

### 2. Data Preprocessing

* Remove missing values.
* Clean review text.
* Convert text into suitable format for BERT.

### 3. Exploratory Data Analysis (EDA)

* Analyze review distributions.
* Study review lengths.
* Examine rating patterns.
* Visualize sentiment distributions.

### 4. Sentiment Analysis using BERT

* Tokenize reviews using BERT tokenizer.
* Fine-tune the pre-trained BERT model.
* Train the sentiment classification model.
* Generate sentiment predictions.

### 5. Aspect Extraction

* Identify movie-related aspects from reviews.
* Create aspect dictionaries.
* Filter relevant aspect terms.

### 6. Aspect-Based Sentiment Analysis (ABSA)

* Analyze sentiment for each extracted aspect.
* Classify aspect sentiment as positive or negative.
* Generate aspect-level sentiment datasets.

### 7. Model Evaluation

* Calculate Accuracy Score.
* Generate Classification Report.
* Compare performance metrics.

---

## 📊 Results

* BERT Sentiment Analysis Accuracy: 85.0%
* ABSA Accuracy Before Dictionary Filtering: 85.7%
* ABSA Accuracy After Dictionary Filtering: 86.3%

### Key Findings

* BERT effectively captures contextual information from movie reviews.
* Aspect-Based Sentiment Analysis provides deeper insights into user opinions.
* Dictionary filtering improves sentiment classification performance.
* Aspect-level analysis helps identify strengths and weaknesses of movies.

---

## 📈 Output Generated

* Sentiment Prediction Results
* Aspect Sentiment Dataset
* Accuracy Comparison Charts
* Performance Evaluation Reports
* Visualizations and Graphs

---

## 🚀 Future Enhancements

* Multi-Class Sentiment Classification
* Real-Time Review Analysis
* Deployment using Flask or Streamlit
* Support for Multiple Domains
* Integration with Recommendation Systems
* Enhanced Aspect Extraction Techniques

---

## 📚 Applications

* Movie Review Analysis
* Customer Feedback Analysis
* Product Review Mining
* Opinion Mining
* Business Intelligence
* Social Media Sentiment Analysis

---

## 👨‍💻 Author

**Yaswitha**

---

## ⭐ Conclusion

This project demonstrates the effectiveness of BERT for sentiment analysis and aspect-based sentiment analysis on IMDb movie reviews. By combining contextual language understanding with aspect-level opinion mining, the system provides detailed and accurate sentiment insights that can be useful for businesses, researchers, and recommendation platforms.
