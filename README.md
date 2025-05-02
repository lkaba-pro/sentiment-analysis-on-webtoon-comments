
# 📚 Lore Olympus Comment Sentiment Analysis using Pre-trained BERT

This project performs **sentiment analysis** on user comments from chapters of the *Lore Olympus* webtoon using a **pre-trained BERT model** from Hugging Face.

## 🎯 Objective

To analyze the emotional tone of reader comments on *Lore Olympus* episodes and gain insights into audience reactions and engagement using natural language processing.

## 📁 Project Structure

- `Lore_Olympus_Sentiment_Analysis_using_Pre_trained_BERT_model.ipynb` – Main Jupyter Notebook for the sentiment analysis pipeline.
- Input data: a CSV file containing user comments and associated chapter metadata.
- Model used: [`nlptown/bert-base-multilingual-uncased-sentiment`](https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment).

## ⚙️ Pipeline Overview

1. **Library Imports**  
   Import necessary libraries: `pandas`, `transformers`, `torch`, `selenium`, etc.

2. **Data Collection: web scraping, data cleaning**  
   Setting the driver, loading the comments and formatting the data into a dataframe for the task.

3. **Quick Exploratory Data Analysis (EDA)**  
   Display sample data, check for missing values, and visualize comment distributions.

4. **Text Preprocessing**  
   Clean comment text by removing special characters, punctuation, emojis, and extra whitespace etc.

5. **Sentiment Prediction with BERT**  
   Apply the `nlptown/bert-base-multilingual-uncased-sentiment` model to classify each comment’s sentiment (1 to 5 stars/score).

6. **Insights/ Visualization**  
   General statistics: Sentiment distribution across comments; Likes &dislikes per sentiment score distribution. 

7. **Improvement strategies**  
   1. Enhance sentiment analysis with Emotion Analysis (distribution, wordcloud ) to clarify ambigous comments and improve sentiment classification and visualization of trends to assess reader reactions over time.

## 🚀 How to Run

1. Clone or download the repository.
2. Open the Jupyter notebook (`.ipynb`) using JupyterLab, VS Code, or Google Colab.
3. Execute all cells in order to reproduce the analysis.

## 🔮 Future Enhancements

- Adding LLM and implementing a dashboard to monitor reader sentiment in real time.
- Improve text processing for comments containing japanese emojis (ex: 〜(꒪꒳꒪)〜ヽ(*ﾟｰヽ(*ﾟｰﾟ*)ﾉ)
- Improve sarcasm detection or more nuanced emotional signals to enhance sentiment classification.

## 👤 Author

Developed by @lkaba-pro as part of a project to explore reader sentiment using NLP techniques and pre-trained language models.
