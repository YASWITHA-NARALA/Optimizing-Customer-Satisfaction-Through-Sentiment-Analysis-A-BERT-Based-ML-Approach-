#BERT-Based Sentiment Analysis on IMDb Reviews

Project Overview:
This project implements Sentiment Analysis using BERT (Bidirectional Encoder Representations from Transformers) on the IMDb movie reviews dataset. The model classifies reviews into sentiment categories and further performs Aspect-Based Sentiment Analysis (ABSA) to identify sentiments associated with specific movie-related aspects such as acting, direction, story, screenplay, music, and more.

Features:
Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Review length and rating analysis
Sentiment classification using BERT
Aspect extraction from movie reviews
Aspect-Based Sentiment Analysis (ABSA)
Performance evaluation using accuracy and classification metrics
Visualization of model performance

Dataset:
The project uses the IMDb Reviews Dataset, containing:
Review Text
Movie Title
User Rating
Sentiment Labels

Technologies Used:
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
PyTorch
Hugging Face Transformers
BERT

Workflow:
Load and preprocess IMDb review data.
Perform exploratory data analysis.
Clean and tokenize review text.
Fine-tune a pre-trained BERT model.
Predict review sentiments.
Extract movie-related aspects from reviews.
Perform aspect-level sentiment classification.
Evaluate model performance using:
Accuracy Score
Classification Report
Export aspect sentiment results.

Results:
Model	Accuracy
BERT (Pretrained)	85.0%
Aspect-Based Sentiment (Before Dictionary Filtering)	85.7%
Aspect-Based Sentiment (After Dictionary Filtering)	86.3%
The aspect-based approach improved sentiment classification performance by focusing on movie-specific aspects.

Output:
The project generates:
Sentiment predictions
Aspect-level sentiment predictions
Accuracy comparison charts
aspect_sentiment_dataset.csv

Example Output:
{
    "acting": "Positive",
    "story": "Negative",
    "music": "Positive"
}

Installation:

Clone the repository:
git clone https://github.com/your-username/bert-sentiment-analysis.git
cd bert-sentiment-analysis

Install dependencies:
pip install -r requirements.txt

Run the notebook:
jupyter notebook

Future Improvements:
Multi-aspect sentiment detection
Real-time review analysis
Deployment using Flask/Streamlit
Support for multiple domains beyond movie reviews

Author:
Yaswitha

License:
This project is intended for educational and research purposes.
