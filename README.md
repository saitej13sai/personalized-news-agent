# Personalized News Feed Agent 📰🤖

This project implements a personalized news recommendation system using a hybrid of collaborative filtering and semantic embeddings (Sentence-BERT). It simulates user interactions and dynamically adapts recommendations based on evolving preferences.

## 🚀 Features
- **Top news fetched using NewsAPI**
- **User interactions simulated** (clicks, likes, time spent)
- **Content-based recommendations** via Sentence-BERT (semantic similarity)
- **Adaptive profiles**: User vectors update with new interactions
- **Visualization**: Bar charts showing top recommendations by similarity

## 📁 Files
- `news_recommendation.ipynb`: Main Colab notebook with full implementation
- `user_interactions.csv`: Simulated interaction dataset
- `README.md`: Project overview and setup instructions
- `output/`: Contains sample visualizations and results (optional)

## 🛠️ Technologies Used
- Python (Pandas, Requests, Scikit-learn, Matplotlib)
- SentenceTransformers (`paraphrase-MiniLM-L6-v2`)
- Google Colab (for rapid prototyping)
- NewsAPI (for fetching live headlines)

## 🧠 Recommendation Logic
1. **Fetch headlines**
2. **Simulate user interactions**
3. **Build user profiles from article content**
4. **Vectorize using Sentence-BERT**
5. **Compute cosine similarity for recommendations**

## 📈 Sample Output
Each user receives 5 top article recommendations, ordered by cosine similarity to their profile. Example:

