# 🎧 Spotify Sentiment Analysis using NLP

> 📊 A data-driven dive into listener emotions — analyzing 10,000+ Spotify user reviews to uncover what the world *really* thinks about music.

---

## 📌 Overview

This project uses **Natural Language Processing (NLP)** to perform **sentiment analysis** on a large dataset of Spotify user reviews. By leveraging Python libraries such as **TextBlob**, **Pandas**, and **Seaborn**, I classified feedback into **Positive**, **Neutral**, or **Negative** sentiments and visualized the emotional tone and subjectivity of listeners.

🎯 **Goal:** Turn unstructured user feedback into actionable, visual sentiment insights.

---

## 🛠️ Tech Stack

| Component        | Tools Used                            |
|------------------|----------------------------------------|
| Language         | Python                                 |
| Data Analysis    | Pandas, NumPy                          |
| Visualization    | Matplotlib, Seaborn, WordCloud         |
| NLP Toolkit      | TextBlob                               |
| Environment      | Google Colab / Jupyter / VS Code       |

---

## 📂 Dataset

- **reviews.csv** — Contains user reviews scraped or collected from Spotify users.  
- The sample was filtered to 10,000 entries to ensure performance and clarity.

---

## 🔍 Methodology

1. **Load & Clean Data:** Removed missing entries, standardized text.
2. **Apply Sentiment Analysis:**
   - Polarity (`-1` to `+1`) indicates negative to positive emotion.
   - Subjectivity (`0` to `1`) measures personal opinion vs. factuality.
3. **Classify Sentiments:**
   - `Positive`: Polarity > 0
   - `Neutral`: Polarity = 0
   - `Negative`: Polarity < 0
4. **Visualize Results:**
   - Bar chart of sentiment categories
   - Subjectivity vs. Polarity scatter plot
   - Word cloud of most-used words in reviews

---



---

## 🚀 How to Run the Project

Clone the repo and execute the script locally or in your notebook environment:

```bash
# Clone this repository
git clone https://github.com/your-username/spotify-sentiment-analysis.git

# Move into the directory
cd spotify-sentiment-analysis

# Install dependencies
pip install -r requirements.txt

# Run the Python script
python sentiment_analysis_of_spotify.py

