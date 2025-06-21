# 🛒 Flipkart Product Review Sentiment Analysis

This project focuses on extracting and analyzing customer sentiments from Flipkart product reviews. It combines web scraping, text processing, and natural language techniques to assess user sentiment based on review polarity.

## 📌 Objective

To analyze customer sentiment about products sold on Flipkart by:
- Scraping product reviews from multiple pages.
- Applying text processing and visualization techniques.
- Identifying positive, negative, and neutral sentiments.

## 🛠️ Technologies Used

- **Python**
- **BeautifulSoup** – Web scraping product reviews
- **Requests** – Sending HTTP requests
- **Pandas & NumPy** – Data cleaning & analysis
- **Matplotlib & WordCloud** – Data visualization
- **TextBlob** – Sentiment polarity analysis
- **Scikit-learn (TfidfVectorizer)** – Text feature extraction (TF-IDF)

## 🔍 Workflow

1. **Web Scraping**  
   - Takes Flipkart product page URL as input  
   - Extracts reviews, customer names, review dates, and ratings

2. **Data Preprocessing**  
   - Clean and organize text data  
   - Remove duplicates, special characters

3. **TF-IDF Matrix Creation**  
   - Represent reviews using TF-IDF for feature extraction

4. **Sentiment Analysis**  
   - Performed using TextBlob's polarity scores  
   - Classifies sentiments as Positive, Negative, or Neutral

5. **Visualization**  
   - WordCloud for most frequent words  
   - Pie chart for sentiment distribution

## 📈 Results

- Most reviews were positive, followed by neutral and negative sentiments.
- WordClouds revealed the most common customer opinions.

## 📂 Files in Repository

flipkart-review-sentiment-analysis/
│
├── flipkart_sentiment_analysis.ipynb # Jupyter Notebook with scraping and analysis
├── README.md # Project documentation
├── requirements.txt # (Optional) List of required Python libraries


## ✅ How to Run

1. Clone the repo or upload the notebook to Jupyter Notebook.
2. Enter a valid Flipkart product URL when prompted.
3. Choose number of review pages to scrape.
4. Run all cells to see sentiment analysis and visualizations.

## ⚠️ Disclaimer

This project is for educational purposes only. Ensure compliance with Flipkart’s [terms of service](https://www.flipkart.com/pages/terms) before scraping data at scale.

---

